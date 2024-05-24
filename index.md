<link rel='stylesheet' href='https://use.fontawesome.com/releases/v5.7.0/css/all.css' integrity='sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ' crossorigin='anonymous'>
<style>
    .project {
        padding-top: 15px;
        padding-bottom: 15px;
    }
    h4 {
        padding-left: 20px;
        color: #f0a1a8;
    }
    .project a.main-nav-item {
        text-decoration: none;
        transition: color 0.3s linear;
        -webkit-transition: color 0.3s linear;
        -moz-transition: color 0.3s linear;
    }
    .project a.main-nav-item:hover {
        color: #ed5a65;
        text-decoration: none;
    }
    .main-nav-item {
        display: inline-block;
    }
    .title {
        display: table;
    }
    .fa-file-alt,
    h4 {
        display: table-cell;
        vertical-align: top;
    }
    .fa-terminal,
    p {
        margin-left: 40px;
        word-wrap: break-word;
    }
    .fa-terminal {
        color: #999;
    }
    .fa-file {
        margin-left: 45px;
        word-wrap: break-word;
        color: #999;
    }
    @media only screen and (max-width: 568px) {
        .fa-file .fa-file {
            margin-left: 10px;
        }
    }
    .fancy-link {
        text-decoration: none;
        transition: color 0.3s linear;
        -webkit-transition: color 0.3s linear;
        -moz-transition: color 0.3s linear;
    }
    .fancy-link:hover {
        color: #ed5a65;
    }
</style>
<body>
    <main>
        <section>
            <h2>Welcome to My Personal Website</h2>
            <p>Hello! I'm Michelle, passionate about risk management. Click <a href="https://michelleziqi.github.io/about%20me/">About Me</a> to get more details </p>
            <p>Below are some of my projects.</p>
        </section>
        <section>
            {% _posts Project %}
        </section>
    </main>
</body>
</html>
