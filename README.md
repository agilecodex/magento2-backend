# magento2-backend
Common Backend Extension for Magento 2

<div id="documenter_content">

<section id="installation">
	<div class="page-header"><h3>Installation</h3><hr class="notop"></div>
<p class="warning">
	Never do anything directly on a live store. First setup and test on a development domain (i.e. “dev.url.com”).</p>
<p class="warning">
	Make sure that you <a href="http://devdocs.magento.com/guides/v2.0/frontend-dev-guide/themes/theme-apply.html#/guides/v2.0/config-guide/cli/config-cli-subcommands-mode.html">set</a> your Magento application to the developer <a href="http://devdocs.magento.com/guides/v2.0/config-guide/bootstrap/magento-modes.html">mode</a>.</p>
<p id="installation_strongtemporarily_disable_magento_cache_strong">
	<strong>Temporarily disable Magento cache</strong></p>
<p>
	To avoid any possible issues with the installation we recommend disabling Magento cache before proceeding with the installation and re-enabling it once the install is complete.</p>
<ol>
	<li>
		Log in to your Magento admin</li>
	<li>
		Go to System &gt; Cache Management</li>
	<li>
		Select “Select All” in the “Mass Actions” drop down</li>
	<li>
		Select “Disable” in the “Actions” drop down and Click Submit</li>
	<li>
		Once the page reloads <strong>log out of the admin</strong></li>
</ol>
<p id="installation_strongupload_oxy_theme_files_strong">
	<strong>Upload Acx Backend</strong></p>
<p>
	Using your favorite <a href="http://lifehacker.com/5039956/five-best-ftp-clients" target="_blank" title="Free FTP tools">FTP client</a>, upload all files and folders to the <strong>root folder</strong> of your Magento installation</p>
<p id="installation_strongtemporarily_disable_magento_cache_strong">
	<strong>Install Extension</strong></p>
<ol>
	<li>
		&nbsp;Enable Acx_Backend module. How to enable magento 2 module, follow this <a href="https://www.agilecodex.com/enable-and-disable-magento-2-module/">link</a>.</li>
</ol>
<div class="alert alert-success" style="text-align: center;">
	That’s it! You are good to go with <strong>Acx Backend</strong> Extension!</div>
</section>


<section id="thank_you">
	<div class="page-header"><h3>Thank You</h3><hr class="notop"></div>
<p>
	We'd be glad to help you if you have any questions relating to this extension. Thank you so much for looking into this extension.</p>
</section>
