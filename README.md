# Portfolio-website
<!DOCTYPE html>
<html lang="en">
<head>
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> PortFlix – Personal Portfolio Website </title><link rel="preload" as="image" imagesrcset="https://blog.thesimplifieddev.com/wp-content/uploads/2023/01/Portfolio-1-1024x510.jpg 1024w, https://blog.thesimplifieddev.com/wp-content/uploads/2023/01/Portfolio-1-1200x598.jpg 1200w, https://blog.thesimplifieddev.com/wp-content/uploads/2023/01/Portfolio-1.jpg 1324w" imagesizes="(max-width: 860px) 100vw, 860px" /><link rel="preload" as="font" href="https://blog.thesimplifieddev.com/wp-content/themes/smart-mag/css/icons/fonts/ts-icons.woff2?v2.4" type="font/woff2" crossorigin="anonymous" />
    <link rel="stylesheet" href="style.css">
    <link data-minify="1" rel="stylesheet" href="https://blog.thesimplifieddev.com/wp-content/cache/min/1/npm/boxicons@latest/css/boxicons.min.css?ver=1680857252">
</head>
<body>
    <!-- Navbar  Section Start -->
    <header>
        <a href="#">Port  Flix.</a>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </header>
    <!-- Navbar Section End -->
    <!-- Home Section Start -->
    <section id="home">
            <a href="#"></a>
            <a href="#"></a>
            <a href="#"></a>
            <img decoding="async" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%200%200'%3E%3C/svg%3E" alt="" data-lazy-src="main.png"><noscript><img decoding="async" src="main.png" alt=""></noscript><div class='code-block code-block-5' style='margin: 8px 0; clear: both;'>
<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-5779648977849582"
     data-ad-slot="7166561073"></ins>
<script type="rocketlazyloadscript">
     (adsbygoogle = window.adsbygoogle || []).push({});
</script></div>

            Hello, I’m
            <h1>SNEHA SONI</h1>
            <h2>Frontend Developer</h2>
            <p>Lorem ipsum dolor sit amet cons <br> adipisicing elit. Minima, consectetur <br> ullam?</p>
            <a href="#contact">Download CV</a>
    </section>
    <!-- Home Section End -->
    <!-- About Section Start -->
    <section id="about">
            <h2>About Me</h2>
            Introduction
                <img decoding="async" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%200%200'%3E%3C/svg%3E" alt="" data-lazy-src="main.png"><noscript><img decoding="async" src="main.png" alt=""></noscript>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Omnis beatae eius quae ab consequatur est
                    perferendis dicta. Ad repellendus perferendis minus sunt error eos dicta enim accusantium ipsum
                    veniam debitis quasi sint cum fugiat porro quam, blanditiis a ratione quod!</p>
                        Name
                        snehasoni
                <a href="#">Download Cv</a>
    </section>
    <!-- About Section End -->
    <!-- Skills Section Start -->
    <section id="skills">
            <h2>Skills</h2>
            My Skills
                    <h3>HTML</h3>
                    94%
                    <h3>CSS</h3>
                    84%
                    <h3>JavaScript</h3>
                    74%
                <img decoding="async" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%200%200'%3E%3C/svg%3E" alt="Skill" data-lazy-src="main.png"><noscript><img decoding="async" src="main.png" alt="Skill"></noscript>
    </section>
    <!-- Skills Section End -->
    <!-- Services Section Start -->
    <section id="services">
            <h2>Services</h2>
            Our Services
                <h3>Web Development</h3>
                <a href="#">Learn More</a>
                <h3>Backend Development</h3>
                <a href="#">Learn More</a>
                <h3>UI/UX Design</h3>
                <a href="#">Learn More</a>
                <h3>App Development</h3>
                <a href="#">Learn More</a>
    </section>
    <!-- Services Section End -->
    <!-- Contact Section Start -->
    <section id="contact">
            <h2>Contact</h2>
            Connect With Us
            <form action="">
                <input type="text" placeholder="Your Name">
                <input type="email" name="" id="" placeholder="Your Email">
                <textare name="" id="" cols="30" rows="10" placeholder="Write Message Here..."></textare>
                <input type="button" value="Send">
            </form>
    </section>
    <!-- Contact Section End -->
        <h2>Follow Us</h2>
            <a href="#"></a>
            <a href="#"></a>
            <a href="#"></a>
            <a href="#"></a>
    <!-- Javascript -->
<script src="app.js">class RocketElementorAnimation{constructor(){this.deviceMode=document.createElement("span"),this.deviceMode.id="elementor-device-mode",this.deviceMode.setAttribute("class","elementor-screen-only"),document.body.appendChild(this.deviceMode)}_detectAnimations(){let t=getComputedStyle(this.deviceMode,":after").content.replace(/"/g,"");this.animationSettingKeys=this._listAnimationSettingsKeys(t),document.querySelectorAll(".elementor-invisible[data-settings]").forEach(t=>{const e=t.getBoundingClientRect();if(e.bottom>=0&&e.top<=window.innerHeight)try{this._animateElement(t)}catch(t){}})}_animateElement(t){const e=JSON.parse(t.dataset.settings),i=e._animation_delay||e.animation_delay||0,n=e[this.animationSettingKeys.find(t=>e[t])];if("none"===n)return void t.classList.remove("elementor-invisible");t.classList.remove(n),this.currentAnimation&&t.classList.remove(this.currentAnimation),this.currentAnimation=n;let s=setTimeout(()=>{t.classList.remove("elementor-invisible"),t.classList.add("animated",n),this._removeAnimationSettings(t,e)},i);window.addEventListener("rocket-startLoading",function(){clearTimeout(s)})}_listAnimationSettingsKeys(t="mobile"){const e=[""];switch(t){case"mobile":e.unshift("_mobile");case"tablet":e.unshift("_tablet");case"desktop":e.unshift("_desktop")}const i=[];return["animation","_animation"].forEach(t=>{e.forEach(e=>{i.push(t+e)})}),i}_removeAnimationSettings(t,e){this._listAnimationSettingsKeys().forEach(t=>delete e[t]),t.dataset.settings=JSON.stringify(e)}static run(){const t=new RocketElementorAnimation;requestAnimationFrame(t._detectAnimations.bind(t))}}document.addEventListener("DOMContentLoaded",RocketElementorAnimation.run);</script></body>
</html>
