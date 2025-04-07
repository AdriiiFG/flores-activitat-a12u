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
<hr>
    ```bash
    Copiar código
    git clone https://github.com/els_teus_usuari/projecte-markdown.git
    cd projecte-markdown
<hr>

### 3. Afegir introducció i una cita

**Explicació:**
Ara, anem a documentar el projecte amb una introducció bàsica i una cita. Això és una bona pràctica per començar a explicar què fa el projecte.

**Passos a seguir:**

Obre el fitxer README.md i afegeix el següent contingut:
<hr>

```markdown
# Projecte Markdown

Aquest projecte és un exemple per practicar com fer servir Markdown i GitHub.

> “La documentació és tan important com el codi.”
```
<hr>

### 4. Afegir taula de continguts

**Explicació:**
Una taula de continguts ajuda els lectors a trobar fàcilment les seccions importants del teu document. A continuació, afegirem aquesta taula per millorar la navegació.

**Passos a seguir:**

Just sota la introducció, afegeix aquest codi per crear una taula de continguts:
<hr>

```markdown
## Continguts

- [Funcionalitats](#funcionalitats)
- [Taula de dades](#taula-de-dades)
- [Glossari](#glossari)
- [Imatge](#imatge)
- [Enllaços útils](#enllaços-útils)
```
<hr>

5. Afegir funcionalitats i taula de dades
Explicació:
Ara afegirem una descripció de les funcionalitats del projecte i una taula per mostrar dades estructurades.

Passos a seguir:

Afegeix una secció de funcionalitats i una taula de dades al teu fitxer README.md:

<hr>

```markdown

## Funcionalitats

- Registrar usuaris
- Guardar dades
- Exportar informes

## Taula de dades

| Nom     | Rol        | Estat  |
|---------|------------|--------|
| Clara   | Disseny    | Actiu  |
| Jordi   | Backend    | Pausat |
```
<hr>

6. Afegir glossari amb llistes de definició (nou concepte)
Explicació:
Les llistes de definició són útils per proporcionar explicacions o descripcions curtes de termes específics dins del projecte. Aquí utilitzarem aquesta estructura per definir algunes paraules clau del projecte.

Passos a seguir:

Afegeix una nova secció per al glossari:
<hr>

```markdown
## Glossari

**Frontend**  
: Part del projecte que veu l’usuari.

**Backend**  
: Part que gestiona dades i lògica.

**Commit**  
: Enregistrament d’un canvi en el projecte.
```
<hr>

### 7. Afegir una imatge

**Explicació:**
Afegir imatges a la documentació ajuda a fer-la més visual i entenedora. En aquest cas, afegirem una imatge del projecte.

**Passos a seguir:**

Crea una carpeta anomenada img/ dins del teu repositori.

<hr>
```markdown
mkdir img
Afegeix una imatge a la carpeta img/ (per exemple, captura.png).
```
<hr>

Al fitxer README.md, afegeix la imatge:

<hr>

```markdown
## Imatge

![Captura del projecte](img/captura.png)
```
<hr>
