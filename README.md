# 👋 Hi, I'm Kenaz mathukutty!
👩🏻‍💻 Software Engineer sharing about my journey and learnings in tech<br/>
Ken8139/Ken8139 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile. 
You can click the Preview link to take a look at your changes.
--->
<h3 align="center">A passionate frontend developer from India</h3>

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>


<img src="https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/assets/74038190/d48893bd-0757-481c-8d7e-ba3e163feae7" />


 **<img src="https://user-images.githubusercontent.com/108933534/210176487-bb71ad61-85d6-4027-a637-5384e9a95733.gif" width="50" height="50"/>**  **About me**

 
 I’m currently learning Computer Science & Engineering.<br>
<img src="https://64.media.tumblr.com/005e37a86478a9c92da7d4d3d7464b40/2bd29f0062317531-b1/s400x600/c7edc142895bc810339223dfddf2aa57ced0c32b.gif" width="700"/>


# 💻 Tech Stack
<!-- Badges from https://github.com/Ileriayo/markdown-badges -->
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)<br/>
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)


# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=Ken8139&theme=tokyonight&hide_border=true&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=Ken8139&theme=tokyonight&hide_border=true)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Ken8139&theme=tokyonight&hide_border=true&include_all_commits=false&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=Ken8139&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4)

<img src="https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/assets/74038190/0c7eb6ed-663b-4ce4-bfbd-18239a38ba1b" width="800">
<br><br>

<img src="https://64.media.tumblr.com/005e37a86478a9c92da7d4d3d7464b40/2bd29f0062317531-b1/s400x600/c7edc142895bc810339223dfddf2aa57ced0c32b.gif" width="700"/>

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=vertical&theme=tokyonight)







@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
@tailwind base;
@tailwind components;
@tailwind utilities;

/* @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap'); */

html {
  font-family: "Poppins", sans-serif;
  /* background-image: linear-gradient( 110.1deg,  rgba(30,2,83,1) 44.2%, rgba(198,55,160,1) 138.2% ); */
  /* background-image: linear-gradient( 94.3deg,  rgba(26,33,64,1) 10.9%, rgba(81,84,115,1) 87.1% ); */
  /* background-image: linear-gradient( 112.1deg,  rgba(32,38,57,1) 11.4%, rgba(63,76,119,1) 70.2% ); */
  background: rgb(24 24 27);
}

@keyframes rotate360 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

/* Animated Underline Start */
.pass {
  text-decoration: none;
  font-size: 1em;
  position: relative;
  transition: all 0.6s;
}
.pass:before {
  content: "";
  width: 0;
  height: 0.05em;
  position: absolute;
  bottom: 0;
  right: 0;
  background: rgb(254 205 211);
  transition: all 0.3s;
}
.pass:hover:before {
  width: 100%;
  left: 0;
  background: rgb(165 243 252);
}
/* Animated Underline End */

.fade-on-appear {
  animation: fadein 0.5s;
}

@keyframes fadein {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

