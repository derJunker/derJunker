## Hi there 👋
I'm currently doing my Masters in CS and work part time at a software firm.
I like to do fun projects i am passionate about :)

<svg fill="red" viewBox="0 0 600 300" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
        <foreignObject width="100%" height="100%">
            <div xmlns="http://www.w3.org/1999/xhtml" class="content">
                <div class="card">
                    <h2>Currently Testing things :)</h2>
                    <p> Wow so cool! </p>
                </div>
            </div>
            <style>
                :root {
                    --border-radius: .75rem;
                }
                h1, h2, h3, h4, h5, h6, p {
                    margin: 0;
                }
                .content {
                    font-family: Avenir, Montserrat, Corbel, 'URW Gothic', source-sans-pro, sans-serif;
                }
                .content {
                    padding: 4rem;
                }
                .card {
                    border-radius: var(--border-radius);
                    background-color: #212830;
                    padding: 1rem;
                    color: white;
                    border: 1px #656c7633 solid;
                }
                .card {
                    position: relative;

                    &::before,
                    &::after {
                        content: "";
                        position: absolute;
                        inset: -3px;
                        z-index: -1;
                        border-radius: inherit;
                        background-image: conic-gradient(
                                from var(--angle),
                                black .01turn,
                                green .98turn,
                                black 1turn
                        );
                        animation: spin 4s ease-out forwards, hide reverse .5s ease, hide 1s forwards 1.25s ease-out;
                    }
                    

                    &::after {
                        filter: blur(14px);
                    }
                }
                @keyframes hide {
                    to {
                        opacity: 0;
                    }
                }

                @keyframes spin {
                    100% {
                        --angle: 500deg;
                    }
                }

                @property --angle {
                    syntax: "<angle>";
                    initial-value: 0deg;
                    inherits: false;
                }
                body {
                    background: red!important;
                }
            </style>
        </foreignObject>
    </svg>