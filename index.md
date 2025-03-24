<html>
  <body><script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'it'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DUA000002SNJt',
				'DVA_Messaging_TEST_GITHUB',
				'https://dvaexpress--full.sandbox.my.site.com/ESWDVAMessagingTESTGIT1742816797358',
				{
					scrt2URL: 'https://dvaexpress--full.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://dvaexpress--full.sandbox.my.site.com/ESWDVAMessagingTESTGIT1742816797358/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>


  </body>
</html>
