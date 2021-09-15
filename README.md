<!DOCTYPE html>

    <head>
        <meta charset="utf-8"> <!-- there is no closing meta tag -->
        <title>
            Ketlin de Mello Moreira
        </title>
    </head>
    <body>
        <h1>Creating Links</h1>
        <section>
            We can link to a file in the same directory as this html file like this:
            <a href="coursera.html" title="test page"> Liking to a file in the same directory          
            </a>
            <a href="coursera.html" title="other test">
                <div> DIV Linking to a file in the same directory</div>
            </a>
        </section>
        <section>
            <p>
                Let's link a GitHub page!
                <a href="https://github.com/ketlindemello" target="_blank" title="Ketlin's GitHub">Practice coursera</a>

            </p>
        </section>  
        <h1 id="top"> Links to Sections of the same Page</h1>
        <section>
            <ul>
                <li><a href="#section1">#section1</a></li>
                <li><a href="#section6">#section6</a></li>
            </ul>
        </section>   
        <section id="section1">
            <h3>(#section1)</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt ducimus unde maxime fugit nobis quae doloremque dicta exercitationem accusantium nisi libero eveniet aliquam, aut reiciendis non cumque dolorem distinctio eos. Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iusto voluptatem cumque temporibus, quasi mollitia officiis omnis animi quisquam officia? Fuga earum beatae distinctio animi, non a doloremque esse sit ipsam. Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora, et sed. Autem, perferendis ullam? Maiores optio atque culpa aut, alias molestias minus ullam, magnam sequi laboriosam dolorem eligendi veritatis fuga. </p>
            

        </section>
        <section>
            <div>
                <h2><a name="section6">(#section6) Section 6</a></h2>
                <p>
                    Back to top: <a href="#top">Back to Top</a>
                </p>
            </div>
        </section>   
    </body>

