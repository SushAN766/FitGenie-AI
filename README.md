#  AI-Powered Personal Fitness Assistant

A full-stack AI-driven fitness platform designed to revolutionize personal health and wellness through smart workout planning, real-time diet recommendations, and an interactive voice experience.

![Tech Stack](https://img.shields.io/badge/Tech%20Stack-Next.js%20%7C%20React%20%7C%20TailwindCSS%20%7C%20Vapi%20%7C%20Gemini%20AI%20%7C%20Clerk%20%7C%20Convex-blue)

---

## 🔗 Live Demo

 [Visit Demo](https://your-vercel-app.vercel.app)

---


##  Features

-  **AI-Generated Fitness Plans**  
  Personalized workout and diet programs tailored to user preferences and goals.

- 🎙️ **Vapi Voice Assistant**  
  Hands-free, voice-based interaction with your personal fitness AI.

-  **Gemini AI Integration**  
  Real-time responses and intelligent suggestions using Google’s LLM.

-  **Secure Auth with Clerk**  
  Fully managed sign-in/sign-up system with session management.

-  **Convex Realtime DB**  
  Serverless, reactive data store for seamless state management.

-  **Modern UI/UX**  
  Built with TailwindCSS and Shadcn UI components for responsive, elegant design.

- ⚙️ **Next.js Client/Server Optimization**  
  App Router with hybrid rendering for performance and scalability.

---

## 🛠 Tech Stack

- **Frontend:** Next.js 14 (App Router), React, TailwindCSS, Shadcn UI
- **AI & Voice:** Vapi (Voice AI SDK), Gemini AI (Google's LLM)
- **Auth:** Clerk
- **Database:** Convex (serverless DB)
- **Hosting:** Vercel

---

##  Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/Flexora-ai.git
cd Flexora-ai

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Add your Clerk, Convex, Gemini, and Vapi credentials here

# Run the development server
npm run dev
```
##  Environment Variables

Create a `.env.local` file with the following:

```env
CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_key
CONVEX_DEPLOYMENT_URL=your_url
GEMINI_API_KEY=your_key
VAPI_API_KEY=your_key
```
##  Roadmap

- [ ] Add fitness progress tracking and graphs  
- [ ] Integrate wearable device data (e.g. Fitbit, Apple Watch) 
- [ ] Implement community features like forums and groups  
- [ ] Push notifications for reminders and progress 

---

##  Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to [open an issue](https://github.com/SushAN766/Flexora-ai/issues) or submit a pull request.

---

## 📄 License

MIT © [Sushanth](https://github.com/SushAN766)

---

##  Acknowledgements

- [Vapi AI](https://www.vapi.ai/)  
- [Google Gemini](https://deepmind.google/technologies/gemini/)  
- [Clerk](https://clerk.dev/)  
- [Convex](https://www.convex.dev/)  
- [Shadcn UI](https://ui.shadcn.com/)  
- [TailwindCSS](https://tailwindcss.com/)  
- [Next.js](https://nextjs.org/)  

---

##  Deployment (Vercel)

1. **Push to GitHub**  
   Upload your project to a new GitHub repository.

2. **Import into Vercel**  
   Go to [Vercel](https://vercel.com/), sign in, and click **"New Project"**.  
   Select your GitHub repo and proceed with the setup.

3. **Add Environment Variables**  
   In your Vercel project dashboard, navigate to:  
   `Settings > Environment Variables` and add the following:

   ```env
   CLERK_PUBLISHABLE_KEY=your_key
   CLERK_SECRET_KEY=your_key
   CONVEX_DEPLOYMENT_URL=your_url
   GEMINI_API_KEY=your_key
   VAPI_API_KEY=your_key
   ```
4. **Deploy! 🚀**
    Hit Deploy and your AI fitness assistant will be live!

