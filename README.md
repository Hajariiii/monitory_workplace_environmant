# Monitoring Workplace Environment to Achieve Maximum Morker Satisfaction

Afin d'augmenter l'efficience, l'efficacité, la productivité et l'engagement professionnel des salariés, les entreprises doivent répondre aux besoins de leurs salariés en leur offrant de bonnes conditions de travail. Ce projet est un système de monitoring de 2 paramètres environnementaux importants dans l’espace de travail, afin d'obtenir une satisfaction professionnelle maximale des travailleurs


## Run

```bash
pip3 install -r requirements.txt
```

```bash
streamlit run dash.py
```

## Usage

L'application réalise le suivi de 2 paramètres environnementaux : la qualité visuelle et le bruit.
![pic1](https://github.com/Hajariiii/monitory_workplace_environmant/blob/main/pic1.png?raw=true)
![pic2](https://github.com/Hajariiii/monitory_workplace_environmant/blob/main/pic2.png?raw=true)

### La qualité visuelle :
ou luminosité, est estimé en utilisant les techniques de OpenCV. La valeur est ensuite classifiée sur un échelle de 0 à 10.
des valeurs entre 4 et 6 sont considérées optimale pour un office bureautique.

### Le bruit :
l'audio est traité grace à Audioop, une classification est ensuite réalisé selon le niveau du bruit. 
'Soft'
'Moderate'
'Loud'
'Very loud, Consider using hearing protection'
'Uncomfortable,Use hearing protection'
'Painful & Dangerous,Use hearing protection or AVOID!'

### Réalisé par : 
Belrhiti Hajar, Dahhassi Charifa, Hassouane Houda.
