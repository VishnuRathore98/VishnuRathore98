
    <svg fill="none" viewBox="0 0 800 200" width="800" height="200"
      xmlns="http://www.w3.org/2000/svg">
      <foreignObject width="100%" height="100%">
        <div
          xmlns="http://www.w3.org/1999/xhtml">
          <style>
            .container {
              font-family:
                system-ui,
                -apple-system,
                'Segoe UI',
                Roboto,
                Helvetica,
                Arial,
                sans-serif,
                'Apple Color Emoji',
                'Segoe UI Emoji';
              display: flex;
              flex-direction: column;
              align-items: center;
              justify-content: center;
              margin: 0;
              width: 100%;
              height: 200px;
              background-color: #a0f6d2;
              background-size: 300% 200%;
              color: rgba(25,25,25,.75);
              text-align: center;
            }

            .type-writer {
              display: inline-block;
            }

            .line-1{
              width: 100%;
              margin: 0 auto;
              border-right: 2px solid rgba(25,25,25,.75);
              text-align: center;
              white-space: nowrap;
              overflow: hidden;
            }

            /* Animation */
            .anim-typewriter{
              animation:  typewriter 4s steps(44) 1s 1 normal both,
                          blinkTextCursor 500ms steps(44) infinite normal;
            }
            @keyframes typewriter{
              from{width: 0;}
              to{width: 100%;}
            }
            @keyframes blinkTextCursor{
              from{border-right-color: rgba(25,25,25,.75);}
              to{border-right-color: transparent;}
            }
          </style>
          <div class="container">
            <div class="type-writer">
              <h2 class="line-1 anim-typewriter">
                Hello! I am Vishnu Pratap Singh Rathore.
              </h2>
            </div>
            <p>
              developer 👨‍💻 • music addict 🎸 • open source enthusiast🌟 • photography noob 📷 • travel 🥑
            </p>
          </div>
        </div>
      </foreignObject>
    </svg>
