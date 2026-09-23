# Yellow Corner Cafeteria — Order Chat

A chat-style food ordering page for **Yellow Corner Cafeteria, Ajayi Crowther University, Oyo**.
*Nourishing minds, spreading smiles.*

**Live page:** https://YOUR-USERNAME.github.io/YOUR-REPO/

## What it does

- Tap food items to add them to your order (tap again for another portion)
- **Clear** removes one portion at a time
- **Checkout** asks for **Pickup** or **Delivery**
  - Pickup: tap **Submit** to get your receipt and bank details
  - Delivery: type your address, then tap **Submit** to get a receipt with your address and bank details

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app (HTML, CSS and JavaScript) |
| `logo.png` | Cafeteria logo |
| `background.jpg` | Page background |

Keep all three files in the same folder.

## Put it online with GitHub Pages

1. Upload `index.html`, `logo.png`, `background.jpg` and this `README.md` to the **root** of your repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`, and press **Save**.
4. Wait a minute, then open `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

Opening `index.html` on github.com only shows the code. GitHub Pages is what runs it.

## Change the payment details

Open `index.html`, find this block near the top of the `<script>` and edit it:

```js
const BANK = {
  bank:'YOUR BANK NAME',
  name:'Yellow Corner Cafeteria',
  number:'0000000000'
};
```

## Change the menu or prices

Edit the `MENU` and `DRINKS` lists in the same script.
