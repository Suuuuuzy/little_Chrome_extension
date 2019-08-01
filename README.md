# little_Chrome_extension

a simple Chrome extension to detect users' behavior

to enable the sending of message, the test page should contain :

`chrome.runtime.sendMessage(targetExtensionId, {type: 'MsgFromPage', msg: 'Hello, I am page~'}, function(response) {
  		console.log(response);
		});`

the targetExtensionId can be found in Chrome extension page:


   
