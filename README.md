# AidminSolutions.github.io
Embedded Bot for Botpress

<html>
  <head>
    <img>https://1drv.ms/i/s!AlZjCd44kiXEgbtlHbg0PA0IxkGWfQ?e=AeP6SU</img>
    <title>Aidmin Customer Service Bot</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
 
    <style>
      body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 10px;
        color: white;
        background-color: #000000;
        font-family: Arial, sans-serif;
      }
 
      .center-div {
        width: 70vw;
        height: 80vh;
        background-color: rgb(102, 71, 255);
        border-radius: 15px;
        padding: 5px;
        box-sizing: border-box;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
      }
 
      @media only screen and (max-width: 600px) {
        .center-div {
          height: 40vh;
          width: 80vw;
          background-color: rgb(102, 71, 255);
          border-radius: 15px;
          padding: 5px;
          box-sizing: border-box;
          color: white;
          display: flex;
          justify-content: center;
          align-items: center;
          text-align: center;
        }
      }
    </style>
  </head>
 
  <body>
    <div>
      <p style="text-align: center;">Botpress Chatbot in a <span><</span><span>div></span></p>
      <div class="absolute inset-4 ">
        <div
          class="center-div relative h-full w-full overflow-clip rounded-md border border-zinc-200 bg-white p-2 px-0 py-0"
        >
          <iframe
            style="border: none;"
            srcdoc="<body><script src='https://cdn.botpress.cloud/webchat/v0/inject.js'></script>
            <script>
              window.botpressWebChat.init({
                  'composerPlaceholder': 'Ask me anything',
                  'botConversationDescription': 'Aidmin Solutions 24/7 Support',
                  'botId': '1dd16d14-c423-43ee-942b-e810d8ab4565',
                  'botName': 'Adam',
                  'hostUrl': 'https://cdn.botpress.cloud/webchat/v0',
                  'messagingUrl': 'https://messaging.botpress.cloud',
                  'clientId': '1dd16d14-c423-43ee-942b-e810d8ab4565',
                  'enableConversationDeletion': true,
                  'showPoweredBy': true,
                  'className': 'webchatIframe',
                  'containerWidth': '100%25',
                  'layoutWidth': '100%25',
                  'hideWidget': true,
                  'showCloseButton': false,
                  'disableAnimations': true,
                  'closeOnEscape': false,
                  'showConversationsButton': false,
                  'enableTranscriptDownload': false,
                  'stylesheet':'https://webchat-styler-css.botpress.app/prod/f4ce8ad4-0160-4b2d-9267-b181e5daba30/v58864/style.css'
                  
              });
            window.botpressWebChat.onEvent(function () { window.botpressWebChat.sendEvent({ type: 'show' }) }, ['LIFECYCLE.LOADED']);
            </script></body>"
            width="100%"
            height="100%"
          ></iframe>
        </div>
      </div>
    </div>
  </body>
</html>
