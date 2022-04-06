<template>
  <div className="container">
      <div id="jsonview">
        <pre>
          {`
{  `}{" "}
          <span className="com">{`// don't select`}</span>{" "}
          {`
 `}
          <span className="key">"name"</span> :
          <span className="val">{` "RAKOTONDRASOA"`}</span>,<br />
          <span className="key"> "last-name" </span>: [
          <span className="val">"Rivo", "Ruddy", "Harifetra"</span>],
          <br />
          <span className="key"> "born on"</span>:
          <span className="val"> "08-11-1994"</span>,<br />
          <span className="key"> "address"</span>:
          <span className="val"> "127.0.0.1:8080"</span>, <br />
          <span className="key"> "contact"</span>: &#123;
          <br />
          <span className="key"> &nbsp;&nbsp;"phone"</span>: [
          <span className="val">"+261326630829"</span>],
          <br />
          <a href="mailto:rrruddyh@gmail.com,vladshining@gmail.com,nca49.io@gmail.com">
            <span className="key"> &nbsp;&nbsp;"mail"</span>: [<br />
            <span className="val"> &nbsp; &nbsp; "rrruddyh@gmail.com"</span>,
            <br />
            <span className="val"> &nbsp; &nbsp; "vladshining@gmail.com"</span>,
            <br />
            <span className="val"> &nbsp; &nbsp; "nca49.io@gmail.com"</span>
            <br />
          </a>
          &nbsp; &nbsp; ],
          <br />
          <span className="key"> &nbsp;&nbsp;"link"</span>: {`{`}
          <br />
          <a href="https://nca-49.web.app/user?name=admin">
            <span className="key"> &nbsp; &nbsp; "web"</span>:{" "}
            <span className="val">
              "https://nca-49.web.app/user?name=admin"
            </span>
          </a>
          ,
          <br />
          <a href="https://github.com/VladShining">
            <span className="key"> &nbsp; &nbsp; "github"</span>:
            <span className="val"> "https://github.com/VladShining"</span>
          </a>
          ,<br />
          <a href="https://facebook.com/NCA49">
            <span className="key"> &nbsp; &nbsp; "facebook"</span>:
            <span className="val"> "https://facebook.com/NCA49"</span>
          </a>
          ,<br />
          <a href="https://www.linkedin.com/in/ruddy-harifetra-8a23101a3/">
            <span className="key"> &nbsp; &nbsp; "linkedin"</span>:
            <span className="val">
              {" "}
              "https://www.linkedin.com/in/ruddy-
              {`
                  harifetra-8a23101a3/"`}
            </span>
          </a>
          , <br />
          <a href="https://codepen.io/vladshining">
            <span className="key"> &nbsp; &nbsp; "codepen"</span>:
            <span className="val"> "https://codepen.io/vladshining"</span>
          </a>
          {`
    }
  },
  `}
          <span className="key">"lang"</span>: [ <br />
          &nbsp; &nbsp; &#123;
          <span className="key"> "langue"</span>:
          <span className="val"> "English" </span>,
          <span className="key"> "level"</span>:
          <span className="val"> "50%" </span>&#125;,
          <br />
          &nbsp; &nbsp; &#123; <span className="key">"langue"</span>:
          <span className="val"> "Francais" </span>,
          <span className="key"> "level"</span>:
          <span className="val"> "80%" </span>&#125;,
          <br />
          &nbsp; &nbsp; &#123; <span className="key">"langue"</span>:
          <span className="val"> "Japan" </span>,
          <span className="key"> "level"</span>:
          <span className="val"> "30%" </span>&#125;,
          <br />
          &nbsp; &nbsp; &#123; <span className="key">"langue"</span>:
          <span className="val"> "Latina" </span>,
          <span className="key"> "level"</span>:
          <span className="val"> "20%" </span>&#125;,
          <br />
          &nbsp; &nbsp; &#123; <span className="key">"langue"</span>:
          <span className="val"> "Malagasy" </span>,
          <span className="key"> "level"</span>:
          <span className="val"> "100%" </span>&#125;,
          <br />
          &nbsp;&nbsp;],
          <br />
          <span className="key">&nbsp; "hobby"</span>: [ <br />
          <span className="val">
            &nbsp; &nbsp;&nbsp;"Drawing and painting any type of art"
          </span>
          ,<br />
          <span className="val">&nbsp; &nbsp;&nbsp;"Video Game Maker"</span>,
          <br />
          <span className="val">&nbsp; &nbsp;&nbsp;"Shooting (picture)"</span>,
          <br />
          <span className="val">&nbsp; &nbsp;&nbsp;"Cooking"</span>,<br />
          &nbsp;&nbsp;],
          <br />
          <span className="key">&nbsp; "personality"</span>: [<br />
          <span className="val">&nbsp; &nbsp;&nbsp;"Autodidact"</span>,
          <br />
          <span className="val">&nbsp; &nbsp;&nbsp;"Soft friendly"</span>,
          <br />
          <span className="val">&nbsp; &nbsp;&nbsp;"Idealist"</span>,
          <br />
          <span className="val">&nbsp; &nbsp;&nbsp;"Qualitative"</span>,
          <br />
          <span className="val">&nbsp; &nbsp;&nbsp;"..."</span>,<br />
          &nbsp;&nbsp;],
          <br />
          <span className="key">&nbsp; "study"</span>: [<br />
          &nbsp; &nbsp; &#123;
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"year" </span>:
          <span className="val">&nbsp; "2013-2015"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"location" </span>:
          <span className="val">&nbsp; "ESPA"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"education" </span>:
          <span className="val">&nbsp; "LICENCE"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"record" </span>:
          <span className="val">&nbsp; "electronique"</span>,<br />
          &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &#123;
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"year" </span>:
          <span className="val">&nbsp; "2015-2018"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"location" </span>:
          <span className="val">&nbsp; "ESPA"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"education" </span>:
          <span className="val">&nbsp; "MASTER"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"record" </span>:
          <span className="val">&nbsp; "Informatique Appliquée"</span>,<br />
          &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; ],
          <br />
          <span className="key">&nbsp; "work"</span>: [<br />
          &nbsp; &nbsp; &#123;
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"when" </span>:
          <span className="val">&nbsp; "Juillet-2019,Novembre-2019"</span>,
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"where" </span>:
          <span className="val">&nbsp; "ITRAS"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"what" </span>:
          <span className="val">&nbsp; "Training Web development"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"job" </span>:
          <span className="val">
            &nbsp; "I learn web architecture and try some
            <br /> &nbsp; &nbsp; &nbsp; language development"
          </span>
          ,<br />
          &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &#123;
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"when" </span>:
          <span className="val">&nbsp; "Novembre-2019,à ce jour"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"where" </span>:
          <span className="val">&nbsp; "DreamsLab"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"what" </span>:
          <span className="val">&nbsp; "Quality tester Web"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"job" </span>:
          <span className="val">
            &nbsp; "I'm in charge of product quality before production"
          </span>
          ,<br />
          &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; ],
          <br />
          <span className="key">&nbsp; "skill"</span>: [<br />
          &nbsp; &nbsp; &#123;
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"title"</span>:
          <span className="val">&nbsp;"Web development"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"detail"</span>: [ <br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Create a web static"
          </span>
          ,
          <br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"build application with Javascript"
          </span>
          ,<br />
          <span className="val">&nbsp; &nbsp; &nbsp; &nbsp;"Designing UI"</span>
          <br />
          &nbsp; &nbsp; &nbsp; ]
          <br />
          &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &#123;
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"title"</span>:
          <span className="val">&nbsp;"Game development"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"detail"</span>: [ <br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Making video game with Unity3D"
          </span>
          ,
          <br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Build game for Android,Web and software"
          </span>
          ,<br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Designing 2D or 3D game with Photoshop
            and Blender"
          </span>
          <br />
          &nbsp; &nbsp; &nbsp; ]
          <br />
          &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &#123;
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"title"</span>:
          <span className="val">&nbsp;"Electronic designer"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"detail"</span>: [ <br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Simulate electronic circuit"
          </span>
          ,
          <br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Build electronic system"
          </span>
          ,<br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Creat and programing electronic system
            automation"
          </span>
          <br />
          &nbsp; &nbsp; &nbsp; ]
          <br />
          &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &#123;
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"title"</span>:
          <span className="val">&nbsp;"System administrator"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"detail"</span>: [ <br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Install firmware , software and hardware
            in windows"
          </span>
          ,
          <br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Configure network"
          </span>
          <br />
          &nbsp; &nbsp; &nbsp; ]
          <br />
          &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &#123;
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"title"</span>:
          <span className="val">&nbsp;"UI/UX designer web and Integrator"</span>
          ,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"detail"</span>: [ <br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Build any media with Adobe Photoshop,
            Illustrator, Xd,<br>&nbsp; &nbsp; &nbsp; &nbsp;After Effect and
            Premier"
          </span>
          ,
          <br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Integrate design with application"
          </span>
          ,<br />
          <span className="val">
            &nbsp; &nbsp; &nbsp; &nbsp;"Animate Web application"
          </span>
          <br />
          &nbsp; &nbsp; &nbsp; ]
          <br />
          &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &#123;
          <br />
          <span className="key">&nbsp; &nbsp; &nbsp;"title"</span>:
          <span className="val">&nbsp;"Programing language skill"</span>
          ,<br />
          <span className="key">&nbsp; &nbsp; &nbsp;"detail"</span>: [ <br />
          &nbsp; &nbsp;&nbsp; &nbsp; &#123;<span className="key"> "lang"</span>:
          <span className="val"> "C/C++"</span>,
          <span className="key"> "skill"</span>:
          <span className="num"> 70 </span>&#125;,
          <br />
          &nbsp; &nbsp;&nbsp; &nbsp; &#123;<span className="key"> "lang"</span>:
          <span className="val"> "C#"</span>,
          <span className="key"> "skill"</span>:
          <span className="num"> 40 </span>&#125;,
          <br />
          &nbsp; &nbsp;&nbsp; &nbsp; &#123;<span className="key"> "lang"</span>:
          <span className="val"> "JavaScript/TypeScript"</span>,
          <span className="key"> "skill"</span>:
          <span className="num"> 70 </span>&#125;,
          <br />
          &nbsp; &nbsp;&nbsp; &nbsp; &#123;<span className="key"> "lang"</span>:
          <span className="val"> "Php or Java or Python"</span>,
          <span className="key"> "skill"</span>:
          <span className="val"> "Hello World !" </span>&#125;,
          <br />
          &nbsp; &nbsp; &nbsp; ]
          <br />
          &nbsp; &nbsp; &#125;
          <br /> &nbsp; ],
          <br />
          <span className="key">&nbsp; "project"</span>: [<br />
          &nbsp; &nbsp; &#123; <br />
          <span className="key">&nbsp; &nbsp; &nbsp; "unit"</span>:
          <span className="val"> "nca-49"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; "overview"</span>: [<br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#123; <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "title"
          </span>
          :
          <a href="https://harifetra.web.app/">
            <span className="val"> "portfolio-49"</span>
          </a>
          ,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "demo"</span>
          :<span className="val"> "https://harifetra.web.app/"</span>
          ,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "about"
          </span>
          :<span className="val"> "Just a website"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "made"</span>
          : [
          <span className="key">
            "HTML5", "Scss/Sass", "ReactJs", "Gsap","..."
          </span>
          ],
          <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "open-source"
          </span>
          :<span className="bool"> true</span>
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#123; <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "title"
          </span>
          :
          <a href="https://foodie-49.web.app/">
            <span className="val"> "Foodie"</span>
          </a>
          ,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "demo"</span>
          :<span className="val"> "https://foodie-49.web.app/"</span>
          ,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "about"
          </span>
          :<span className="val"> "web app for food recip"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "made"</span>
          : [
          <span className="key">
            "Angular", "Scss", "Firebase/firestore", "..."
          </span>
          ],
          <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "open-source"
          </span>
          :<span className="bool"> true</span>
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#123; <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "title"
          </span>
          :
          <a href="https://platform-49.web.app/">
            <span className="val"> "Board"</span>
          </a>
          ,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "demo"</span>
          :<span className="val"> "https://platform-49.web.app/"</span>
          ,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "about"
          </span>
          :<span className="val"> "web app for task organization"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "made"</span>
          : [
          <span className="key">
            "React", "react-dnd", "Firebase/firestore", "..."
          </span>
          ],
          <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "open-source"
          </span>
          :<span className="bool"> true</span>
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#123; <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "title"
          </span>
          :
          <a href="https://nca-49.web.app/">
            <span className="val"> "NCA-49"</span>
          </a>
          ,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "demo"</span>
          :<span className="val"> "https://nca-49.web.app/"</span>
          ,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "about"
          </span>
          :
          <span className="val">
            {" "}
            "my web platfom to teach electronic for you"
          </span>
          ,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "made"</span>
          : [
          <span className="key">
            "Angular", "NestJs", "Firebase/firestore", "NodeJS"
          </span>
          ],
          <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "open-source"
          </span>
          :<span className="bool"> false</span>
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &#125;, <br />
          &nbsp; &nbsp; &#123; <br />
          <span className="key">&nbsp; &nbsp; &nbsp; "unit"</span>:
          <span className="val"> "iot-49"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; "overview"</span>: [<br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#123; <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "title"
          </span>
          :<span className="val"> "clever house"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "demo"</span>
          :<span className="val"> "https://"</span>
          ,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "about"
          </span>
          :<span className="val"> "Project house automation"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "made"</span>
          : [<span className="key">"Arduino", "Nodemcu"</span>
          ],
          <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "open-source"
          </span>
          :<span className="bool"> true</span>
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#123; <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "title"
          </span>
          :<span className="val"> "rover bot"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "demo"</span>
          :<span className="val"> "https://"</span>
          ,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "about"
          </span>
          :<span className="val"> "Just a patrol bot"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "made"</span>
          : [<span className="key">"Arduino", "Sparkfun"</span>
          ],
          <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "open-source"
          </span>
          :<span className="bool"> true</span>
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#123; <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "title"
          </span>
          :<span className="val"> "AVA"</span>,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "about"
          </span>
          :<span className="val"> "Automatic virtual assistant"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "made"</span>
          : [<span className="key">"Linux shell", "Python", "orangePi"</span>
          ],
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &#125;, <br />
          &nbsp; &nbsp; &#123; <br />
          <span className="key">&nbsp; &nbsp; &nbsp; "unit"</span>:
          <span className="val"> "unity game"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; "overview"</span>: [<br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#123; <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "title"
          </span>
          :<span className="val"> "Tower defense"</span>,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "demo"</span>
          :<span className="val"> "https://"</span>
          ,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "about"
          </span>
          :<span className="val"> "tower defense game for windows"</span>,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "source"
          </span>
          :<span className="val"> "https://"</span>
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#123; <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "title"
          </span>
          :
          <a href="https://drive.google.com/file/d/1A1yEREDMo5Rg8QeZt_f8KQR67CJRaGaU/view?usp=sharing">
            <span className="val"> "HLS"</span>
          </a>
          ,<br />
          <span className="key">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "demo"</span>
          :
          <span className="val">
            {" "}
            "https://drive.google.com/file/d/
            <br />
            {"           "} 1A1yEREDMo5Rg8QeZt_f8KQR67CJRaGaU/view?usp=sharing"
          </span>
          ,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "about"
          </span>
          :
          <span className="val">
            {" "}
            "Home Light Simulator , a light simulator .<br />
            {"           "} I made it for my master presentation"
          </span>
          ,<br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#123; <br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "title"
          </span>
          :<span className="val"> "RPG platformer"</span>,<br />
          <span className="key">
            &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; "about"
          </span>
          :<span className="val"> "An RPG game"</span>,<br />
          &nbsp; &nbsp; &nbsp; &nbsp; &#125;,
          <br />
          &nbsp; &nbsp; &#125;, <br />
          &nbsp;&nbsp;],
          <br />
          <span className="key">&nbsp; "picture"</span>:
          <span className="val"> "https://404NotFound"</span>,<br />
          <span className="key">&nbsp; "thanks"</span>: &#123;
          <br />
          <span className="key"> &nbsp; &nbsp;"OC"</span>:
          <span className="val">"https://openclassrooms.com/"</span>
          ,<br />
          <span className="key"> &nbsp; &nbsp;"Coursera"</span>:
          <span className="val"> "https://fr.coursera.org/"</span>,
          <br />
          <span className="key"> &nbsp; &nbsp;"Fireship"</span>:
          <span className="val"> "https://fireship.io/"</span>,
          <br />
          <span className="key"> &nbsp; &nbsp;"Egghead"</span>:
          <span className="val"> "https://egghead.io/"</span>,
          <br />
          <span className="key"> &nbsp; &nbsp;"Css Trick"</span>:
          <span className="val"> "https://css-tricks.com/"</span>,
          <br />
          <span className="key"> &nbsp; &nbsp;"Grafikart"</span>:
          <span className="val"> "https://grafikart.fr/"</span>,
          <br />
          <span className="key"> &nbsp; &nbsp;"Stackoverflow"</span>:
          <span className="val">"https://stackoverflow.com/"</span>
          ,<br />
          <span className="key"> &nbsp; &nbsp;"etc"</span>:
          <span className="val"> "..."</span>
          <br />
          &nbsp; &nbsp;],
          <br />
          <span className="key">&nbsp; "copyright"</span>:
          <span className="val">
            `"©{ date.getFullYear().toString() } 493.649"`
          </span>
          {`
}


        `}
        </pre>
      </div>
    </div>
</template>

<style lang="scss">
#jsonview {
  background-color: #222222;
  background: url("../assets/Tile2.svg");
  background-size: 13px;
  background-repeat: repeat;
  font-family: "Consolas", "Courier New", monospace;
  font-size: 12px;
  letter-spacing: normal;
  pre {
    color: white;
    .com {
      color: greenyellow;
    }
    .key {
      color: #62cdff;
    }
    .val {
      color: #e0742c;
    }
    .num {
      color: #d6f171;
    }
    .bool {
      color: blue;
    }
  }
  a {
    color: inherit;
    text-decoration: none;
    :hover {
      text-decoration: underline;
    }
  }
}
</style>
