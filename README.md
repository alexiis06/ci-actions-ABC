# CI Actions XXX

![CI](https://github.com/EL-TEU-USUARI/ci-actions-XXX/actions/workflows/ci.yml/badge.svg)

## 🧪 Projecte de proves amb GitHub Actions

Aquest repositori forma part de la pràctica de **Integració Contínua (CI)** amb **GitHub Actions**.  
L’objectiu és configurar un pipeline que:

- Executi els tests automàticament en cada `push` i `pull_request`
- Provi el projecte amb diverses versions de PHP (8.1, 8.2 i 8.3)
- Generi un informe JUnit
- Pugi els resultats com a artefacte
- Mostri una insígnia amb l’estat del workflow

---

## 📁 Estructura del projecte
ci-actions-XXX/
├── src/
│   └── Calculadora.php
├── tests/
│   └── CalculadoraTest.php
├── composer.json
├── phpunit.xml
└── .github/
└── workflows/
├── hola.yml
└── ci.yml


---

## ⚙️ Workflows inclosos

### **Hola Actions XXX**
Workflow senzill que es pot executar manualment i mostra un missatge al log.

### **CI XXX**
Pipeline complet que:
- Instal·la dependències
- Configura PHP (matriu 8.1 / 8.2 / 8.3)
- Executa PHPUnit
- Genera `resultats.xml`
- Desa l’artefacte `resultats-XXX`

---

## ▶️ Execució dels tests en local
composer install
./vendor/bin/phpunit

---

## 📦 Artefactes

Cada execució del workflow CI genera un artefacte descarregable:


---

## 📝 Notes

- La carpeta `vendor/` no es puja al repositori.
- Els workflows han d’estar dins `.github/workflows/`.
- La indentació del YAML és **sempre amb espais**.

---

## 👤 Autor

Projecte creat per **XXX** com a part de la pràctica de GitHub Actions.
