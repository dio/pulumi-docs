
---
title: "GetStorageAccount"
title_tag: "Function GetStorageAccount | Module databoxedge | Package Azure NextGen"
meta_desc: "Explore the GetStorageAccount function of the databoxedge module, including examples, input properties, output properties, and supporting types. "
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->




## Using GetStorageAccount {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getStorageAccount<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx">GetStorageAccountArgs</span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx">GetStorageAccountResult</span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>get_storage_account(</span><span class="nx">device_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">resource_group_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">storage_account_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> GetStorageAccountResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>LookupStorageAccount<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">args</span><span class="p"> *</span><span class="nx">LookupStorageAccountArgs</span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx">LookupStorageAccountResult</span>, error)</span></code></pre></div>

> Note: This function is named `LookupStorageAccount` in the Go SDK.

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetStorageAccount </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx">GetStorageAccountResult</span>> <span class="p">InvokeAsync(</span><span class="nx">GetStorageAccountArgs</span><span class="p"> </span><span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:


{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="devicename_csharp">
<a href="#devicename_csharp" style="color: inherit; text-decoration: inherit;">Device<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The device name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_csharp">
<a href="#resourcegroupname_csharp" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The resource group name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="storageaccountname_csharp">
<a href="#storageaccountname_csharp" style="color: inherit; text-decoration: inherit;">Storage<wbr>Account<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The storage account name.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="devicename_go">
<a href="#devicename_go" style="color: inherit; text-decoration: inherit;">Device<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The device name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_go">
<a href="#resourcegroupname_go" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The resource group name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="storageaccountname_go">
<a href="#storageaccountname_go" style="color: inherit; text-decoration: inherit;">Storage<wbr>Account<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The storage account name.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="devicename_nodejs">
<a href="#devicename_nodejs" style="color: inherit; text-decoration: inherit;">device<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The device name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="resourcegroupname_nodejs">
<a href="#resourcegroupname_nodejs" style="color: inherit; text-decoration: inherit;">resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The resource group name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="storageaccountname_nodejs">
<a href="#storageaccountname_nodejs" style="color: inherit; text-decoration: inherit;">storage<wbr>Account<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The storage account name.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="device_name_python">
<a href="#device_name_python" style="color: inherit; text-decoration: inherit;">device_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The device name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="resource_group_name_python">
<a href="#resource_group_name_python" style="color: inherit; text-decoration: inherit;">resource_<wbr>group_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The resource group name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="storage_account_name_python">
<a href="#storage_account_name_python" style="color: inherit; text-decoration: inherit;">storage_<wbr>account_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The storage account name.{{% /md %}}</dd>
</dl>
{{% /choosable %}}




## GetStorageAccount Result {#result}

The following output properties are available:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="blobendpoint_csharp">
<a href="#blobendpoint_csharp" style="color: inherit; text-decoration: inherit;">Blob<wbr>Endpoint</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}BlobEndpoint of Storage Account{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="containercount_csharp">
<a href="#containercount_csharp" style="color: inherit; text-decoration: inherit;">Container<wbr>Count</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The Container Count. Present only for Storage Accounts with DataPolicy set to Cloud.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_csharp">
<a href="#id_csharp" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path ID that uniquely identifies the object.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_csharp">
<a href="#name_csharp" style="color: inherit; text-decoration: inherit;">Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The object name.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_csharp">
<a href="#type_csharp" style="color: inherit; text-decoration: inherit;">Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hierarchical type of the object.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="datapolicy_csharp">
<a href="#datapolicy_csharp" style="color: inherit; text-decoration: inherit;">Data<wbr>Policy</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Data policy of the storage Account.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="description_csharp">
<a href="#description_csharp" style="color: inherit; text-decoration: inherit;">Description</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Description for the storage Account.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="storageaccountcredentialid_csharp">
<a href="#storageaccountcredentialid_csharp" style="color: inherit; text-decoration: inherit;">Storage<wbr>Account<wbr>Credential<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Storage Account Credential Id{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="storageaccountstatus_csharp">
<a href="#storageaccountstatus_csharp" style="color: inherit; text-decoration: inherit;">Storage<wbr>Account<wbr>Status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Current status of the storage account{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="blobendpoint_go">
<a href="#blobendpoint_go" style="color: inherit; text-decoration: inherit;">Blob<wbr>Endpoint</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}BlobEndpoint of Storage Account{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="containercount_go">
<a href="#containercount_go" style="color: inherit; text-decoration: inherit;">Container<wbr>Count</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The Container Count. Present only for Storage Accounts with DataPolicy set to Cloud.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_go">
<a href="#id_go" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path ID that uniquely identifies the object.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_go">
<a href="#name_go" style="color: inherit; text-decoration: inherit;">Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The object name.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_go">
<a href="#type_go" style="color: inherit; text-decoration: inherit;">Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hierarchical type of the object.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="datapolicy_go">
<a href="#datapolicy_go" style="color: inherit; text-decoration: inherit;">Data<wbr>Policy</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Data policy of the storage Account.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="description_go">
<a href="#description_go" style="color: inherit; text-decoration: inherit;">Description</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Description for the storage Account.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="storageaccountcredentialid_go">
<a href="#storageaccountcredentialid_go" style="color: inherit; text-decoration: inherit;">Storage<wbr>Account<wbr>Credential<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Storage Account Credential Id{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="storageaccountstatus_go">
<a href="#storageaccountstatus_go" style="color: inherit; text-decoration: inherit;">Storage<wbr>Account<wbr>Status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Current status of the storage account{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="blobendpoint_nodejs">
<a href="#blobendpoint_nodejs" style="color: inherit; text-decoration: inherit;">blob<wbr>Endpoint</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}BlobEndpoint of Storage Account{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="containercount_nodejs">
<a href="#containercount_nodejs" style="color: inherit; text-decoration: inherit;">container<wbr>Count</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}The Container Count. Present only for Storage Accounts with DataPolicy set to Cloud.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_nodejs">
<a href="#id_nodejs" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The path ID that uniquely identifies the object.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_nodejs">
<a href="#name_nodejs" style="color: inherit; text-decoration: inherit;">name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The object name.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_nodejs">
<a href="#type_nodejs" style="color: inherit; text-decoration: inherit;">type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hierarchical type of the object.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="datapolicy_nodejs">
<a href="#datapolicy_nodejs" style="color: inherit; text-decoration: inherit;">data<wbr>Policy</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Data policy of the storage Account.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="description_nodejs">
<a href="#description_nodejs" style="color: inherit; text-decoration: inherit;">description</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Description for the storage Account.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="storageaccountcredentialid_nodejs">
<a href="#storageaccountcredentialid_nodejs" style="color: inherit; text-decoration: inherit;">storage<wbr>Account<wbr>Credential<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Storage Account Credential Id{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="storageaccountstatus_nodejs">
<a href="#storageaccountstatus_nodejs" style="color: inherit; text-decoration: inherit;">storage<wbr>Account<wbr>Status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Current status of the storage account{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="blob_endpoint_python">
<a href="#blob_endpoint_python" style="color: inherit; text-decoration: inherit;">blob_<wbr>endpoint</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}BlobEndpoint of Storage Account{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="container_count_python">
<a href="#container_count_python" style="color: inherit; text-decoration: inherit;">container_<wbr>count</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}The Container Count. Present only for Storage Accounts with DataPolicy set to Cloud.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_python">
<a href="#id_python" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The path ID that uniquely identifies the object.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="name_python">
<a href="#name_python" style="color: inherit; text-decoration: inherit;">name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The object name.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_python">
<a href="#type_python" style="color: inherit; text-decoration: inherit;">type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hierarchical type of the object.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="data_policy_python">
<a href="#data_policy_python" style="color: inherit; text-decoration: inherit;">data_<wbr>policy</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Data policy of the storage Account.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="description_python">
<a href="#description_python" style="color: inherit; text-decoration: inherit;">description</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Description for the storage Account.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="storage_account_credential_id_python">
<a href="#storage_account_credential_id_python" style="color: inherit; text-decoration: inherit;">storage_<wbr>account_<wbr>credential_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Storage Account Credential Id{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="storage_account_status_python">
<a href="#storage_account_status_python" style="color: inherit; text-decoration: inherit;">storage_<wbr>account_<wbr>status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Current status of the storage account{{% /md %}}</dd>
</dl>
{{% /choosable %}}





<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-azure-nextgen">https://github.com/pulumi/pulumi-azure-nextgen</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
</dl>

