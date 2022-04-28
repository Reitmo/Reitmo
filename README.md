- 👋 Hi, I’m @Reitmo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Reitmo/Reitmo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
- islamrashik9@gmail
(() => {


    const DOMString = `<div class="the-brave-coders__backdrop">
                        <div class="the-brave-coders__popup">
                            <a href="https://www.youtube.com/c/TheBraveCoders/" class="the-brave-coders__popup-header" target="_blank">
                                <i class="ri-youtube-fill the-brave-coders__btn-icon"></i>TheBraveCoders
                            </a>

                            <h1 class="the-brave-coders__code-name">
                                <span class="the-brave-coders__code-name--span">Subscribe Our Youtube Channel</span>😋
                            </h1>

                            <a href="https://youtube.com/c/TechTalkTV" class="the-brave-coders__link"
                                target="_blank">https://youtube.com/c/TechTalkTV</a>
                            <a href="#" class="the-brave-coders__ok-btn">Ok</a>
                        </div>
                    </div>
                    <div class="the-brave-coders-learn-it">
                        <a href="https://youtube.com/c/TechTalkTV" class="the-brave-coders-learn-it__button" target="_blank">
                            <i class="ri-youtube-fill the-brave-coders__btn-icon"></i>
                            Our Youtube Channel
                        </a>
                    </div>`



    const createLinkElementAndAppendInHead = (path) => {
        const element = document.createElement('link');
        element.href = `${path}`;
        element.rel = 'stylesheet';
        document.head.append(element);
    }






    
