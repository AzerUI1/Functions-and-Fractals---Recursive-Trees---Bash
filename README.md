```markdown

<h1 align="center"> Functions & Fractals — Recursive Trees (Bash)</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Author-Azer%20Aslanov-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Topic-Recursive%20Fractals-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Language-Bash-4EAA25?style=for-the-badge&logo=gnubash" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

<p align="center">
  <b>Fractal trees implemented using recursion in pure Bash. A minimal, elegant science-themed project created for the Science & Genius channel.</b>
</p>

---

## Animated Preview (GIF)
<p align="center">
  <img src="https://media.giphy.com/media/3oEduQAsYcJKQH2XsI/giphy.gif" width="80%" />
</p>

---

##  Features
-  Recursive fractal tree drawing in Bash  
-  Clean recursive logic  
-  No external dependencies  
-  Works perfectly in dark terminal  
-  GIF preview for demonstration  
-  Made by **Azer Aslanov**  

---

##  Project Structure

Your repo currently contains:

```

📦 Functions-and-Fractals---Recursive-Trees---Bash
┣ 📜.gitignore
┣ 📜LICENSE
┣ 📜README.md
┗ 📜Functions-and-Fractals

````

The Bash solution is inside the folder **Functions-and-Fractals/**.

---

##  Bash Script (Example)

If your file is named something else, replace it here.

```bash
draw_tree() {
    local depth=$1
    local indent=$2

    if [ "$depth" -le 0 ]; then
        return
    fi

    printf "%${indent}s|\n"
    printf "%${indent}s*\n"

    draw_tree $((depth - 1)) $((indent - 1))
    draw_tree $((depth - 1)) $((indent + 1))
}

draw_tree 5 20
````

---

##  How to Run

Inside your repo:

```bash
cd Functions-and-Fractals
chmod +x fractal_tree.sh
./fractal_tree.sh
```

---

##   Screenshot

<p align="center">
  <img src="https://via.placeholder.com/900x400/000000/FFFFFF?text=Recursive+Tree+Output" width="85%" />
</p>

---

##  Demo Button

<p align="center">
  <a href="https://github.com/AzerU11/Functions-and-Fractals---Recursive-Trees---Bash">
    <img src="https://img.shields.io/badge/View_Repository-Click_Here-6f42c1?style=for-the-badge" />
  </a>
</p>

---

## 🔧 License

This project is licensed under the MIT License — see the **LICENSE** file for details.

---

##  Support the Project

If you like this fractal project, please **star the repo** 

---

## 🔗 Connect With Me

<p align="left">
  <a href="https://github.com/AzerU11">
    <img src="https://img.shields.io/badge/GitHub-AzerU11-000000?style=for-the-badge&logo=github" />
  </a>
</p>
```

---

