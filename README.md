# 📏 Drag Ruler Integration Symbaroum — Foundry VTT

**Drag Ruler Integration Symbaroum** is a fan-made module that adds support for the **Drag Ruler** module in the **Symbaroum** RPG system on **Foundry VTT (v12+)**.

It calculates and displays movement range bands when dragging tokens on the battlemap based on Symbaroum's combat movement rules.

---

## ⚙️ How it Works / Como Funciona

In Symbaroum, a character can perform up to **two movement actions** in a combat round (each representing a displacement of 10 meters/paces by default):
* **Walk (Ação de Movimento):** Represents 1 movement action (default: 10 meters). Shown as a **Green** band.
* **Run (Corrida / 2 Ações):** Represents 2 movement actions (default: 20 meters). Shown as an **Orange** band.

---

## 💾 Installation / Instalação

You can install this module manually or by using the Manifest URL in Foundry VTT:

### Manifest URL (Link de Manifesto)
Copy the link below and paste it in the **Manifest URL** field inside the **Add-on Modules** tab in Foundry VTT Setup:

```text
https://raw.githubusercontent.com/Crespo7777/symbaroum-ruler/main/module.json
```

### Manual Installation (Instalação Manual)
1. Download the ZIP file of the module from your repository.
2. Extract it into your Foundry VTT user data modules folder:
   * `%localappdata%\FoundryVTT\Data\modules\symbaroum-ruler`
3. Ensure the `module.json` is located directly inside the `symbaroum-ruler` folder.
4. Launch Foundry VTT, go to your Symbaroum world, and activate **Drag Ruler Integration Symbaroum** (and make sure the **Drag Ruler** module is also active).

---

## 🔧 Configuration / Configuração

You can customize the base movement speed of the characters:
1. Go to **Game Settings** (Configure Settings) in Foundry VTT.
2. Under the module settings for **Drag Ruler Integration Symbaroum**, you can adjust the base movement speed value (Default: `10`).
