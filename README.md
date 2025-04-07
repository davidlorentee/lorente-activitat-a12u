# Activitat de Repàs 

Aquesta activitat el que farem és fer alguns conceptes que hem fet a classe i els repassàrem.

També afegirem com posar-hi una imatge. 

L'objectiu d'aquesta activitat de repàs és perquè pugis repassar conceptes de Markdown abans de l'examen

## Crear un nou repositori 

Primer has d'anar al teu perfil de GitHub i creàs un nou repositori per exemple que es digui 
### 
    Activitat-de-Repàs 

Recorda, per crear el teu repositori:

1. Clicar Create repository.

2. Per clonar el repositori a la carpeta /c/projectes del teu ordinador.

3. Copia l'enllaç que proporciona GitHub (https://github.com/< el-teu-usuari >/Activitat-de-Repàs).

4. Obre el terminal de Git Bash dins de VS Code.

5. Escriure la següent comanda per anar a C:\ :
###
    cd /c/projectes

6. Clonar el repositori:

### 
    git clone (https://github.com/<el-teu-usuari>/Activitat-de-Repàs)

7. Entra a la carpeta del projecte que acaba de crear el git clone que has fet:

###
    cd Activitat-de-Repàs 

8. Crea el fitxer README.md amb les instruccions de l’activitat que has creat.

Ara dins del README.md hauràs de crear els següents conceptes.



## Crerar Titol 
El nom del Titul ha da ser "Activitat de Repàs"

 Per fer-ho en format de titulo has de posari un "#" 

###
```markdown
# Activitat de Repàs
```

## Fer el commit 

Un commit guarda els canvis del nostre projecte.

Jo faig un commit a cada titul 

Instruccions 

1. Comprovar l'estat del repositori:

### git status

2. Prepara tots els fitxers modificats per desar-los.

### 
    git add .

3.  Desa els canvis amb una descripció.

### 
    git commit -m "titol"

4. Puja aquests canvis al teu dipòsit a GitHub.

### 
    git push -u origin main

Conclusió

Amb aquestes ordres pots treballar en el teu projecte amb seguretat: veus els canvis, els prepares, els guardes i els puges al núvol. És la base per portar un bon control de versions amb Git i GitHub.

## Creació d'una taula
Ara el que vull que hi fagis és fer una creació d'una taula

Vull que hi creis una taula amb ("Els Teus Punts Forts a l'hora de treballar tant tu sol tant amb equip").



### 
Aquí t'adjunto una ajuda de la taula.
|    Solitari   | En equip |
|---------------|----------|
|               |          |

```markdown
|    Solitari   | En equip |
|---------------|----------|
|               |          |
```

