<h1 align="center">💪 AI Fitness Assistant 🤖</h1>

<p align="center">
  🧠 <b>Your Personalized AI-Powered Workout & Diet Companion</b> 💪🥗<br />
  A modern full-stack fitness assistant built with <b>Next.js</b> ⚛️, <b>Tailwind CSS</b> 🎨, <b>Shadcn UI</b> 🧩, and <b>Vapi Voice AI</b> 🎙️.<br />
  Integrated with <b>Gemini AI</b> 🤖 for real-time workout and diet generation ⚡.<br />
  Designed to help you stay fit, eat smart, and train better — all in a clean, responsive UI. 🚀🏋️‍♂️
  <br /><br />
</p>

![Demo App](https://github.com/Gauravpatil07/Codeflex---AI-Fitness-Assistant/blob/7b77e5b8d6b8369675300af1f1f4f12fc1abde16/screenshot-for-readme.png)

## ✨ Highlights:

* 🚀 **Tech stack**: Next.js, React, Tailwind & Shadcn UI
* 🎙️ **Voice AI Assistant** (Vapi)
* 🧠 **LLM Integration** (Gemini AI)
* 🏋️ **Personalized Workout Plans**
* 🥗 **Custom Diet Programs**
* 🔒 **Authentication & Authorization** (Clerk)
* 💾 **Database** (Convex)
* 🎬 **Real-time Program Generation**
* 💻 **Layouts**
* 🎭 **Client & Server Components**

## 🌟 Features

* 🤖 **Smart AI Assistant**: Engage in conversation with an AI that asks about your fitness goals, physical condition, and preferences
* 🧘 **Personalized Workout Plans**: Get custom exercise routines based on your fitness level, injuries, and goals
* 🍱 **Diet Recommendations**: Receive personalized meal plans accounting for your allergies and dietary preferences
* 🔐 **User Authentication**: Sign in with GitHub, Google, or email/password
* 📋 **Program Management**: Create and view multiple fitness programs with only the latest one active
* 📱 **Responsive Design**: Beautiful UI that works across all devices

## ⚙️ Setup `.env` file

```js
# 🔐 Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# 🔁 Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# 🧠 Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# 💾 Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

## 🚀 Getting Started

1. 🔁 **Clone** the repository
2. 📦 **Install dependencies**:

```bash
npm install
```

3. 🧪 **Set up your environment variables** as shown above
4. 🏃‍♂️ **Run the development server**:

```bash
npm run dev
```

5. 🌐 Open [http://localhost:3000](http://localhost:3000) in your browser

## 🌍 Deployment

This application can be easily deployed to **Vercel**:

```bash
npm run build
npm run start
```

Or connect your GitHub repository to **Vercel** for automatic deployments.

## 🛠️ Technologies Used

* ⚛️ **Next.js**: React framework for building the frontend and API routes
* 🎨 **Tailwind CSS & Shadcn UI**: For styling and UI components
* 🧑‍💼 **Clerk**: Authentication and user management
* 🗣️ **Vapi**: Voice agent platform for conversational AI
* 🔄 **Convex**: Real-time database
* 🧠 **Gemini AI**: Large Language Model for generating personalized fitness programs

## 📚 Learn More

To learn more about the technologies used in this project:

* 📘 [Next.js Documentation](https://nextjs.org/docs)
* 📕 [Clerk Documentation](https://clerk.com/docs)
* 📙 [Vapi Documentation](https://docs.vapi.ai)
* 📗 [Convex Documentation](https://docs.convex.dev)
* 📒 [Gemini AI Documentation](https://ai.google.dev/gemini-api)

---
