<html>
  <body>
	  
	 <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'it'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D06000001barf',
				'DVA_Messaging_Chat',
				'https://dvaexpress.my.site.com/ESWDVAMessagingChat1749052511707',
				{
					scrt2URL: 'https://dvaexpress.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
	/*window.addEventListener("onEmbeddedMessagingReady", e => {
		  embeddedservice_bootstrap.prechatAPI.setVisiblePrechatFields({
			// List the pre-chat field names with the value and whether
			// it's editable in the pre-chat form.
			"Nome / Cognome": {
			  "value": "[QUI IL NOME E COGNOME DELL'UTENTE, RECUPERATI DA LOCAL STORAGE]",
			  "isEditableByEndUser": false
			},
			"ID Utente / Email": {
			  "value": "[L'ID O LA MAIL DELL'UTENTE, RECUPERATI DA LOCAL STORAGE]",
			  "isEditableByEndUser": false
			},
		  });*/
	</script>

	  
	<script type='text/javascript' src='https://dvaexpress.my.site.com/ESWDVAMessagingChat1749052511707/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
