<html>
  <body>
  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'it'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DUA000002SNJt',
				'DVA_Salesforce_Messaging_CHAT',
				'https://dvaexpress--full.sandbox.my.site.com/ESWDVASalesforceMessagi1742377837018',
				{
					scrt2URL: 'https://dvaexpress--full.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://dvaexpress--full.sandbox.my.site.com/ESWDVASalesforceMessagi1742377837018/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>



  </body>
</html>
