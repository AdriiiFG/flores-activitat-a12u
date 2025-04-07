# Activitat: Documentació d’un projecte amb Markdown i GitHub

## Objectiu de l’activitat

L'objectiu d'aquesta activitat és practicar l'ús de **Markdown** per documentar un projecte i utilitzar **GitHub** per gestionar els canvis. En aquesta activitat, aprendrem a utilitzar concepts avançats de Markdown (com taules, imatges, i llistes de definició) i a crear un fitxer `.gitignore` per excloure arxius que no volem seguir al nostre projecte.

---

## Abans de començar

### Requisits previs:

1. **GitHub**: Necessites tenir un compte a GitHub i crear un repositori.
2. **Git**: Necessites tenir Git instal·lat al teu ordinador per poder clonar el repositori i pujar els canvis.
3. **Coneixements bàsics de Git**: Si ja saps com fer commits i fer push a GitHub, estàs llest per començar!

---

## Instruccions detallades pas a pas

A continuació, et donaré els passos que has de seguir. Recorda fer un commit cada vegada que facis un canvi important i que el missatge sigui clar per explicar què has fet.

---

### 🔹 1. Crear el repositori a GitHub

**Explicació:**  
El primer pas és crear un repositori a GitHub on podràs guardar el projecte. Un repositori és com un contenidor en línia per al teu projecte, on pots fer un seguiment de tots els canvis que facis.

**Passos a seguir:**

1. Aneu a [GitHub](https://github.com) i clica sobre "New repository".
2. Dona-li un nom al teu repositori, per exemple, `projecte-markdown`.
3. Marca la casella **“Add a README file”** perquè aquest fitxer sigui creat automàticament quan creïs el repositori.
4. No cal afegir `.gitignore` ni llicència en aquest moment.
5. Clica **Create repository**.

### 2. Clonar el repositori

**Explicació:**
Un cop creat el repositori a GitHub, hem de clonar-lo al nostre ordinador. Això ens permetrà treballar directament des del nostre entorn local.

**Passos a seguir:**

Copia l'URL del repositori des de GitHub (per exemple, https://github.com/els_teus_usuari/projecte-markdown.git).

Obre una terminal o línia de comandes i escriu el següent:

bash
Copiar código
git clone https://github.com/els_teus_usuari/projecte-markdown.git
cd projecte-markdown

### 3. Afegir introducció i una cita

**Explicació:**
Ara, anem a documentar el projecte amb una introducció bàsica i una cita. Això és una bona pràctica per començar a explicar què fa el projecte.

**Passos a seguir:**

Obre el fitxer README.md i afegeix el següent contingut:

markdown
Copiar código

# Projecte Markdown

Aquest projecte és un exemple per practicar com fer servir Markdown i GitHub.

> “La documentació és tan important com el codi.”