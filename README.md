AidminSolutions.github.io
Embedded Bot for Botpress


<title>Botpress in a div</title>
    
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    color: white;
    background-color: #000000;
    font-family: Arial, sans-serif;
  }

  .center-div {
    width: 50vw;
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

    
  

  
  
    

      
Botpress Chatbot in a <div>


      

        

          <iframe
            style="border: none;"
            srcdoc="<script src='https://cdn.botpress.cloud/webchat/v0/inject.js'></script>
            <script>
              window.botpressWebChat.init({
                  'composerPlaceholder': 'Chat with bot',
                  'botConversationDescription': 'Aidmin Solutions 24/7 Support',
                  'botName': 'Adam',
                  'botId': '1dd16d14-c423-43ee-942b-e810d8ab4565',
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
                  'stylesheet':'https://webchat-styler-css.botpress.app/prod/f4ce8ad4-0160-4b2d-9267-b181e5daba30/v97026/style.css'
          });
        window.botpressWebChat.onEvent(function () { window.botpressWebChat.sendEvent({ type: 'show' }) }, ['LIFECYCLE.LOADED']);
        </script></body>"
        width="100%"
        height="100%"
      ></iframe>
    </div>
  </div>
</div>

<script src="https://cdn.botpress.cloud/webchat/v1/inject.js"></script>
