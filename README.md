# 💌 date invitation app

> [!CAUTION]
> default text and UI inside the `index.html` file are in **Polish**. However, you can easily translate the headings and button labels to English (or any other language) directly in the code!

basic and interactive website which is used for asking sb out on a date. Site allows the girl to select time, date and activity! All info is sent through discord channel using webhook

## ✨ features
* **responsive:** is scaled to look quite decent on mobile devices(since it prob will be opened using phone)
* **a lot of customization:** since its HTML you can easily replace some parts/gifs to your preference
* **discord integration:** when provided with webhook, the information - when, which time, what are we doing is sent directly to your discord channel

## 🚀 usability guide

The site is just one file (`index.html`) since the project is relatively small

### Step 1: webhook config (Important!)
To get notified about the response, you need to connect a Discord webhook:
1. Go to your Discord server -> **Server Settings** -> **Integrations** -> **Webhooks**.
2. Create a new Webhook and copy its URL.
3. Open the `index.html` in a code editor.
4. Find this line (around line 300) and put your own webhook there:
   `const WEBHOOK_URL = "---";`

### Step 2: personalization
In the `index.html` code, you can easily change:
* The name in the header (currently: "halo cześć [name]...").
* The GIFs (by replacing the links in the `<img src="...">` tags).
* The options in the `optionsData` object inside the `<script>` section.

## technologies
As mentioned before - the project is not too big, so its only using HTML, CSS, JavaScript
