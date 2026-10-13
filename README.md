# 💊 Dava India

> A web application that helps users find and understand medicines, powered by public datasets and Google's Gemini API.

---

## 📖 About the Project

**Dava India** ("Dava" means *medicine* in Hindi) is a web platform built to make medicine information easier to access for people in India. Users can search for medicines, view details, and receive AI-generated assistance through the Gemini API.

> ⚠️ **Note:** AI-powered features depend on a valid Gemini API key. See [Known Limitations](#-known-limitations).

---

## ✨ Features

- 🔍 Search for medicines by name
- 📋 View medicine details (uses, composition, information)
- 🤖 AI-powered responses using the Gemini API
- 📱 Responsive design for mobile and desktop
- ☁️ Deployed on Vercel for fast global access

*(Edit this list to match the exact features of your site.)*

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | [e.g., React / Next.js / HTML, CSS, JavaScript] |
| Styling | [e.g., Tailwind CSS / CSS3 / Bootstrap] |
| Backend | [e.g., Node.js + Express / Next.js API routes] |
| AI | Google Gemini API |
| Hosting | Vercel |

---

## 📚 Libraries & Dependencies

Main libraries used in this project (see `package.json` for exact versions):

| Library | Purpose |
|---------|---------|
| `[react]` | UI components |
| `[next]` | Framework and routing |
| `[axios]` | HTTP requests to APIs |
| `[@google/generative-ai]` | Gemini API client |
| `[tailwindcss]` | Styling |
| `[dotenv]` | Loading environment variables |

*(Replace with the actual libraries from your `package.json`.)*

---

## 🌐 Public APIs Used

| API | Purpose | Authentication |
|-----|---------|----------------|
| **Google Gemini API** | AI-generated medicine information and responses | API key required (`GEMINI_API_KEY`) |
| [Other public API, if any] | [Purpose] | [None / API key] |

Get a free Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey).

---

## 🗂️ Datasets Used

| Dataset | Source | Description |
|---------|--------|-------------|
| [Dataset name 1] | [Kaggle / data.gov.in / other] | [e.g., Indian medicine names, composition, and uses] |
| [Dataset name 2] | [Source] | [Description] |

*(Add the exact dataset names and links.)*

---

## 🚀 How to Run the Project

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- npm or yarn
- Git
- A Gemini API key

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a file named `.env.local` in the root folder and add:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

> 🔒 Never commit your `.env.local` file or share your API key publicly. Make sure it is listed in `.gitignore`.

### 4. Start the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### 5. Build for Production

```bash
npm run build
npm start
```

---

## ☁️ Deployment

The project is deployed on [Vercel](https://vercel.com).

To deploy your own copy:

1. Push the code to GitHub.
2. Import the repository into Vercel.
3. Go to **Project Settings → Environment Variables** and add `GEMINI_API_KEY`.
4. Click **Deploy**.

---

## ⚠️ Known Limitations

- **Gemini API key not configured:** The deployed version currently does **not** have a working Gemini API key. Because of this, AI-generated results may not appear, or may fail to load.
- **Dataset coverage:** Search results are limited to the medicines included in the datasets used.
- **Not medical advice:** The information shown is for educational purposes only.
- **API rate limits:** Free-tier Gemini keys have usage limits, which may cause temporary failures.

### 🔧 How to Fix the Gemini Limitation

Add a valid `GEMINI_API_KEY` in your local `.env.local` file (for local use) or in Vercel's Environment Variables (for the live site), then redeploy.

---

## 🩺 Disclaimer

This project is built for educational and informational purposes only. It does **not** replace professional medical advice, diagnosis, or treatment. Always consult a qualified doctor or pharmacist before taking any medicine.

---

## 👥 Team Members

This project was built by:

| Name | Role |
|------|------|
| **Kartik Gehlot** | [Role, e.g., Developer] |
| **Keshav Sharma** | [Role, e.g., Developer] |
| **Suraj Gaur** | [Role, e.g., Developer] |
| **Ashwin Singh Chouhan** | [Role, e.g., Developer] |

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🙏 Acknowledgements

- [Google Gemini API](https://ai.google.dev/)
- [Vercel](https://vercel.com)
- Dataset providers listed above
