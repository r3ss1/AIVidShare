<div align="center">
  <br />
    <a href="https://youtu.be/ZBCUegTZF7M?si=ubt0vk70lSjt6DCs" target="_blank">
      <img src="https://i.postimg.cc/5NR9bxFM/Sora-README.png" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/NativeWind-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="nativewind" />
  </div>

<h3 align="center">Video Sharing App</h3>

   <div align="center">
     In this project, I am following along with Adrian Hajdin from JavaScript Mastery (YouTube) to build a video sharing application. 



</div>
</div>
<div align="center">
    <br><br>
    <a href="https://www.youtube.com/watch?v=ZBCUegTZF7M&t=976s&ab_channel=JavaScriptMastery" target="_blank">Project Video</a>
    <br>
    <a href="https://github.com/adrianhajdin" target="_blank">Adrian Hajdin GitHub</a>
</div>
<br>
<div align="center">
    <br><br>
    <a href="https://www.youtube.com/watch?v=kmy_YNhl0mw&t=2072s&ab_channel=JavaScriptMastery" target="_blank">Project Video</a>
    <br>
    <a href="https://github.com/adrianhajdin" target="_blank">Adrian Hajdin GitHub</a>
</div><br>
<div style="text-align: center; margin-top: 20px;">
    <table style="
        margin: 0 auto; 
        width: 80%;
        border-radius: 8px;
        border-collapse: collapse;
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        text-align: center;">
        <thead style="background-color: #336699; color: white;">
            <tr>
                <th style="padding: 15px; font-size: 15px; border-bottom: 2px solid #ddd;text-align: center;">Initiated</th>
                <th style="padding: 15px; font-size: 15px; border-bottom: 2px solid #ddd;text-align: center;">Completed</th>
                <th style="padding: 15px; font-size: 15px; border-bottom: 2px solid #ddd;text-align: center;">Progress - 29Dec24</th>
                <th style="padding: 15px; font-size: 15px; border-bottom: 2px solid #ddd;text-align: center;">YT video lenght</th>
            </tr>
        </thead>
        <tbody style="background-color: #f9f9f9;">
            <tr>
                <td style="padding: 12px; font-size: 16px; color: #336699; font-weight: bold; text-align: center;">December 2024</td>
                <td style="padding: 12px; font-size: 16px; color: #336699; font-weight: bold; text-align: center;">Est. ~ mid 2025</td>
                <td style="padding: 12px; font-size: 16px; color: #336699; font-weight: bold; text-align: center;">
                    <div style="background-color: #4caf50; width: 2px; height: 20px; border-radius: 10px; margin: 0 auto; text-align: center;"></div>
                    2%
                </td>
                <td style="padding: 12px; font-size: 16px; color: #336699; font-weight: bold; text-align: center;"> 4 hours </td>
            </tr>
        </tbody>
    </table>
</div>

## <a name="introduction">🤖 Introduction</a>

Built with React Native for seamless user experiences, Animatable for captivating animations, and integrated with the dependable backend systems of Appwrite,
this app showcases impressive design and functionality, enabling seamless sharing of AI videos within the community.

If you're getting started and need assistance or face any bugs, join our active Discord community with over 27k+ members. It's a place where people help each other out.

<a href="https://discord.com/invite/n6EdbFJ" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/618f4872-1e10-42da-8213-1d69e486d02e" /></a>

## <a name="tech-stack">⚙️ Tech Stack</a>

- React Native
- Expo
- Nativewind
- Animatable
- Appwrite

## <a name="features">🔋 Features</a>

👉 **Onboarding Screen**: Engaging graphics and clear instructions welcome users to the app.

👉 **Robust Authentication & Authorization System**: Secure email login safeguards user accounts.

👉 **Dynamic Home Screen with Animated Flat List**: Smoothly animated flat list showcases the latest videos for seamless browsing.

👉 **Pull-to-Refresh Functionality**: Users can refresh content with a simple pull gesture for up-to-date information.

👉 **Full-Text Search Capability**: Efficiently search through videos with real-time suggestions and instant results.

👉 **Tab Navigation**: Navigate between sections like Home, Search, and Profile with ease using tab navigation.

👉 **Post Creation Screen for Uploading Media**: Upload video and image posts directly from the app with integrated media selection.

👉 **Profile Screen with Detailed Insights**: View account details and activity, including uploaded videos and follower count, for a personalized experience.

👉 **Responsiveness**: Smooth performance and adaptability across various devices and screen sizes for a consistent user experience.

👉 **Animations**: Dynamic animations using the Animatable library to enhance user interaction and engagement throughout the app's UI.

and many more, including code architecture and reusability

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/r3ss1/AIVidShare.git
cd main_AIVidShare
```
**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm start
```

**Expo Go**

Download the [Expo Go](https://expo.dev/go) app onto your device, then use it to scan the QR code from Terminal and run.

## <a name="snippets">🕸️ Snippets</a>

<details>
<summary><code>tailwind.config.js</code></summary>

```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./app/**/*.{js,jsx,ts,tsx}", "./components/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {
      colors: {
        primary: "#161622",
        secondary: {
          DEFAULT: "#FF9C01",
          100: "#FF9001",
          200: "#FF8E01",
        },
        black: {
          DEFAULT: "#000",
          100: "#1E1E2D",
          200: "#232533",
        },
        gray: {
          100: "#CDCDE0",
        },
      },
      fontFamily: {
        pthin: ["Poppins-Thin", "sans-serif"],
        pextralight: ["Poppins-ExtraLight", "sans-serif"],
        plight: ["Poppins-Light", "sans-serif"],
        pregular: ["Poppins-Regular", "sans-serif"],
        pmedium: ["Poppins-Medium", "sans-serif"],
        psemibold: ["Poppins-SemiBold", "sans-serif"],
        pbold: ["Poppins-Bold", "sans-serif"],
        pextrabold: ["Poppins-ExtraBold", "sans-serif"],
        pblack: ["Poppins-Black", "sans-serif"],
      },
    },
  },
  plugins: [],
};
```

</details>

<details>
<summary><code>Font Loaded</code></summary>

```javascript
const [fontsLoaded, error] = useFonts({
  "Poppins-Black": require("../assets/fonts/Poppins-Black.ttf"),
  "Poppins-Bold": require("../assets/fonts/Poppins-Bold.ttf"),
  "Poppins-ExtraBold": require("../assets/fonts/Poppins-ExtraBold.ttf"),
  "Poppins-ExtraLight": require("../assets/fonts/Poppins-ExtraLight.ttf"),
  "Poppins-Light": require("../assets/fonts/Poppins-Light.ttf"),
  "Poppins-Medium": require("../assets/fonts/Poppins-Medium.ttf"),
  "Poppins-Regular": require("../assets/fonts/Poppins-Regular.ttf"),
  "Poppins-SemiBold": require("../assets/fonts/Poppins-SemiBold.ttf"),
  "Poppins-Thin": require("../assets/fonts/Poppins-Thin.ttf"),
});

useEffect(() => {
  if (error) throw error;

  if (fontsLoaded) {
    SplashScreen.hideAsync();
  }
}, [fontsLoaded, error]);

if (!fontsLoaded && !error) {
  return null;
}
```

</details>

<details>
<summary><code>Dummy Videos for Appwrite</code></summary>

```javascript
const videos = [
  {
    title: "Get inspired to code",
    thumbnail:
      "https://i.ibb.co/tJBcX20/Appwrite-video.png",
    video:
      "https://player.vimeo.com/video/949579770?h=897cd5e781",
    prompt:
      "Create a motivating AI driven video aimed at inspiring coding enthusiasts with simple language",
  },
  {
    title: "How AI Shapes Coding Future",
    thumbnail:
      "https://i.ibb.co/Xkgk7DY/Video.png",
    video:
      "https://player.vimeo.com/video/949581999?h=4672125b31",
    prompt: "Picture the future of coding with AI. Show AR VR",
  },
  {
    title: "Dalmatian's journey through Italy",
    thumbnail:
      "https://i.ibb.co/CBYzyKh/Video-1.png",
    video:
      "https://player.vimeo.com/video/949582778?h=d60220d68d",
    prompt:
      "Create a heartwarming video following the travels of dalmatian dog exploring beautiful Italy",
  },
  {
    title: "Meet small AI friends",
    thumbnail:
      "https://i.ibb.co/7XqVPVT/Photo-1677756119517.png",
    video:
      "https://player.vimeo.com/video/949616422?h=d60220d68d",
    prompt:
      "Make a video about a small blue AI robot blinking its eyes and looking at the screen",
  },
  {
    title: "Find inspiration in Every Line",
    thumbnail:
      "https://i.ibb.co/mGfCYJY/Video-2.png",
    video:
      "https://player.vimeo.com/video/949617485?h=d60220d68d",
    prompt:
      "A buy working on his laptop that sparks excitement for coding, emphasizing the endless possibilities and personal growth it offers",
  },
  {
    title: "Japan's Blossoming temple",
    thumbnail:
      "https://i.ibb.co/3Y2Nk7q/Bucket-215.png",
    video:
      "https://player.vimeo.com/video/949618057?h=d60220d68d",
    prompt: "Create a captivating video journey through Japan's Sakura Temple",
  },
  {
    title: "A Glimpse into Tomorrow's VR World",
    thumbnail:
      "https://i.ibb.co/C5wXXf9/Video-3.png",
    video:
      "https://player.vimeo.com/video/949620017?h=d60220d68d",
    prompt: "An imaginative video envisioning the future of Virtual Reality",
  },
  {
    title: "A World where Ideas Grow Big",
    thumbnail:
      "https://i.ibb.co/DzXRfyr/Bucket-59038.png",
    video:
      "https://player.vimeo.com/video/949620200?h=d60220d68d",
    prompt:
      "Make a fun video about hackers and all the cool stuff they do with computers",
  },
];
```

</details>

## <a name="links">🔗 Links</a>

Assets and constants used in the project can be found [here](https://drive.google.com/drive/folders/1pckq7VAoqZlmsEfYaSsDltmQSESKm8h7?usp=sharing)

## <a name="more">🚀 More</a>

**Advance your skills with JSM's Next.js Pro Course**

Enjoyed creating this project? Dive deeper into JSM's PRO courses for a richer learning adventure. They're packed with
detailed explanations, cool features, and exercises to boost your skills. Give it a go!

<a href="https://jsmastery.pro/next15" target="_blank">
   <img src="https://github.com/user-attachments/assets/b8760e69-1f81-4a71-9108-ceeb1de36741" alt="Project Banner">
</a>
