---
title: "Module config"
title_tag: "Module config | Package @pulumi/azuredevops | Node.js SDK"
linktitle: "config"
meta_desc: "Explore members of the config module in the @pulumi/azuredevops package."
git_sha: "5a2704baa4eadd2446006775047639ffb3cd5575"
block_external_search_index: true
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

{{< resource-docs-alert "azuredevops" >}}






<h3>APIs</h3>
<ul class="api">
    <li><a href="#orgServiceUrl"><span class="symbol api"></span>orgServiceUrl</a></li>
    <li><a href="#personalAccessToken"><span class="symbol api"></span>personalAccessToken</a></li>
</ul>




<h2 id="apis">APIs</h2>
<h3 class="pdoc-module-header" id="orgServiceUrl" data-link-title="orgServiceUrl">
    <a href="https://github.com/pulumi/pulumi-azuredevops/blob/5a2704baa4eadd2446006775047639ffb3cd5575/sdk/nodejs/config/vars.ts#L12">
        let <strong>orgServiceUrl</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> orgServiceUrl: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;orgServiceUrl&#34;) || utilities.getEnv(&#34;AZDO_ORG_SERVICE_URL&#34;)</span>;</code></pre>

The url of the Azure DevOps instance which should be used.

<h3 class="pdoc-module-header" id="personalAccessToken" data-link-title="personalAccessToken">
    <a href="https://github.com/pulumi/pulumi-azuredevops/blob/5a2704baa4eadd2446006775047639ffb3cd5575/sdk/nodejs/config/vars.ts#L16">
        let <strong>personalAccessToken</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kd'>let</span> personalAccessToken: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;personalAccessToken&#34;) || utilities.getEnv(&#34;AZDO_PERSONAL_ACCESS_TOKEN&#34;)</span>;</code></pre>

The personal access token which should be used.

