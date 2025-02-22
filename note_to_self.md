command line to resize images :
> convert <image_path/image_name.png -resize 1000x1000 new_image_name.png  

example:                                                                                                           
- convert agents.webp -resize 500x500 thumbnail.webp   
- convert agents.webp -resize 1000x1000 main.webp  

------

Clicker sur un lien de fichier present dans le meme dossier post/ (ici un exemple avec requirements.txt de posts/local_agents/)
- [requirements.txt](requirements.txt "$(cat requirements.txt)")

Faire un hover text (et ajouter de la couleur)
#| echo: false
#| output: asis
with open('requirements.txt') as f:
    requirements = f.read().strip()
    
print(f'You can see which dependencies are used for running this notebook by simply hovering over the following : <span style="text-decoration: underline dotted; cursor: help; color:rgb(255, 105, 230);" title="{requirements}">requirements.txt</span>')

------
Ajouter de la couleur dans un mots:
<span style="color:rgb(255, 105, 230);">requirement.txt</span>

