
---
title: "Container"
title_tag: "azure-nextgen.databoxedge.Container"
meta_desc: "Documentation for the azure-nextgen.databoxedge.Container resource with examples, input properties, output properties, lookup functions, and supporting types."
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

Represents a container on the  Data Box Edge/Gateway device.
Latest API Version: 2019-08-01.


{{% examples %}}
## Example Usage

{{< chooser language "typescript,python,go,csharp" / >}}
### ContainerPut
{{% example csharp %}}
```csharp
using Pulumi;
using AzureNextGen = Pulumi.AzureNextGen;

class MyStack : Stack
{
    public MyStack()
    {
        var container = new AzureNextGen.DataBoxEdge.Latest.Container("container", new AzureNextGen.DataBoxEdge.Latest.ContainerArgs
        {
            ContainerName = "blobcontainer1",
            DataFormat = "BlockBlob",
            DeviceName = "testedgedevice",
            ResourceGroupName = "GroupForEdgeAutomation",
            StorageAccountName = "storageaccount1",
        });
    }

}

```

{{% /example %}}

{{% example go %}}

```go
package main

import (
	databoxedge "github.com/pulumi/pulumi-azure-nextgen/sdk/go/azure/databoxedge/latest"
	"github.com/pulumi/pulumi/sdk/v2/go/pulumi"
)

func main() {
	pulumi.Run(func(ctx *pulumi.Context) error {
		_, err := databoxedge.NewContainer(ctx, "container", &databoxedge.ContainerArgs{
			ContainerName:      pulumi.String("blobcontainer1"),
			DataFormat:         pulumi.String("BlockBlob"),
			DeviceName:         pulumi.String("testedgedevice"),
			ResourceGroupName:  pulumi.String("GroupForEdgeAutomation"),
			StorageAccountName: pulumi.String("storageaccount1"),
		})
		if err != nil {
			return err
		}
		return nil
	})
}

```

{{% /example %}}

{{% example python %}}

```python
import pulumi
import pulumi_azure_nextgen as azure_nextgen

container = azure_nextgen.databoxedge.latest.Container("container",
    container_name="blobcontainer1",
    data_format="BlockBlob",
    device_name="testedgedevice",
    resource_group_name="GroupForEdgeAutomation",
    storage_account_name="storageaccount1")

```

{{% /example %}}

{{% example typescript %}}

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as azure_nextgen from "@pulumi/azure-nextgen";

const container = new azure_nextgen.databoxedge.latest.Container("container", {
    containerName: "blobcontainer1",
    dataFormat: "BlockBlob",
    deviceName: "testedgedevice",
    resourceGroupName: "GroupForEdgeAutomation",
    storageAccountName: "storageaccount1",
});

```

{{% /example %}}

{{% /examples %}}


## Create a Container Resource {#create}
{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx">Container</span><span class="p">(</span><span class="nx">name</span><span class="p">:</span> <span class="nx">string</span><span class="p">, </span><span class="nx">args</span><span class="p">:</span> <span class="nx">ContainerArgs</span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nx">Container</span><span class="p">(</span><span class="nx">resource_name</span><span class="p">:</span> <span class="nx">str</span><span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.ResourceOptions">Optional[ResourceOptions]</a></span> = None<span class="p">, </span><span class="nx">container_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">data_format</span><span class="p">:</span> <span class="nx">Optional[Union[str, AzureContainerDataFormat]]</span> = None<span class="p">, </span><span class="nx">device_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">resource_group_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">storage_account_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span><span class="nx">NewContainer</span><span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span><span class="p"> </span><span class="nx">string</span><span class="p">, </span><span class="nx">args</span><span class="p"> </span><span class="nx">ContainerArgs</span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx">Container</span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx">Container</span><span class="p">(</span><span class="nx">string</span><span class="p"> </span><span class="nx">name<span class="p">, </span><span class="nx">ContainerArgs</span><span class="p"> </span><span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
  
    <dt
        class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>
      The unique name of the resource.
    </dd>
  
    <dt
        class="property-required" title="Required">
        <span>args</span>
        <span class="property-indicator"></span>
        <span class="property-type">ContainerArgs</span>
    </dt>
    <dd>
      The arguments to resource properties.
    </dd>
  
    <dt
        class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span>
    </dt>
    <dd>
      Bag of options to control resource&#39;s behavior.
    </dd>
  

</dl>

{{% /choosable %}}

{{% choosable language python %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
        <span class="property-type">
            <a href="/docs/reference/pkg/python/pulumi/#pulumi.ResourceOptions">ResourceOptions</a>
        </span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
  
    <dt
        class="property-optional" title="Optional">
        <span>ctx</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span>
    </dt>
    <dd>
      Context object for the current deployment.
    </dd>
  
    <dt
        class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>
      The unique name of the resource.
    </dd>
  
    <dt
        class="property-required" title="Required">
        <span>args</span>
        <span class="property-indicator"></span>
        <span class="property-type">ContainerArgs</span>
    </dt>
    <dd>
      The arguments to resource properties.
    </dd>
  
    <dt
        class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span>
    </dt>
    <dd>
      Bag of options to control resource&#39;s behavior.
    </dd>
  

</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
  
    <dt
        class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>
      The unique name of the resource.
    </dd>
  
    <dt
        class="property-required" title="Required">
        <span>args</span>
        <span class="property-indicator"></span>
        <span class="property-type">ContainerArgs</span>
    </dt>
    <dd>
      The arguments to resource properties.
    </dd>
  
    <dt
        class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>
    </dt>
    <dd>
      Bag of options to control resource&#39;s behavior.
    </dd>
  

</dl>

{{% /choosable %}}

## Container Resource Properties {#properties}

To learn more about resource properties and how to use them, see [Inputs and Outputs]({{< relref "/docs/intro/concepts/programming-model#outputs" >}}) in the Programming Model docs.

### Inputs

The Container resource accepts the following [input]({{< relref "/docs/intro/concepts/programming-model#outputs" >}}) properties:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="containername_csharp">
<a href="#containername_csharp" style="color: inherit; text-decoration: inherit;">Container<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The container name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="dataformat_csharp">
<a href="#dataformat_csharp" style="color: inherit; text-decoration: inherit;">Data<wbr>Format</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string | <a href="#azurecontainerdataformat">Pulumi.<wbr>Azure<wbr>Next<wbr>Gen.<wbr>Data<wbr>Box<wbr>Edge.<wbr>Azure<wbr>Container<wbr>Data<wbr>Format</a></span>
    </dt>
    <dd>{{% md %}}DataFormat for Container{{% /md %}}</dd>
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
    <dd>{{% md %}}The Storage Account Name{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="containername_go">
<a href="#containername_go" style="color: inherit; text-decoration: inherit;">Container<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The container name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="dataformat_go">
<a href="#dataformat_go" style="color: inherit; text-decoration: inherit;">Data<wbr>Format</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string | <a href="#azurecontainerdataformat">Azure<wbr>Container<wbr>Data<wbr>Format</a></span>
    </dt>
    <dd>{{% md %}}DataFormat for Container{{% /md %}}</dd>
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
    <dd>{{% md %}}The Storage Account Name{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="containername_nodejs">
<a href="#containername_nodejs" style="color: inherit; text-decoration: inherit;">container<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The container name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="dataformat_nodejs">
<a href="#dataformat_nodejs" style="color: inherit; text-decoration: inherit;">data<wbr>Format</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string | <a href="#azurecontainerdataformat">Azure<wbr>Container<wbr>Data<wbr>Format</a></span>
    </dt>
    <dd>{{% md %}}DataFormat for Container{{% /md %}}</dd>
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
    <dd>{{% md %}}The Storage Account Name{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="container_name_python">
<a href="#container_name_python" style="color: inherit; text-decoration: inherit;">container_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The container name.{{% /md %}}</dd>
    <dt class="property-required"
            title="Required">
        <span id="data_format_python">
<a href="#data_format_python" style="color: inherit; text-decoration: inherit;">data_<wbr>format</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str | <a href="#azurecontainerdataformat">Azure<wbr>Container<wbr>Data<wbr>Format</a></span>
    </dt>
    <dd>{{% md %}}DataFormat for Container{{% /md %}}</dd>
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
    <dd>{{% md %}}The Storage Account Name{{% /md %}}</dd>
</dl>
{{% /choosable %}}


### Outputs

All [input](#inputs) properties are implicitly available as output properties. Additionally, the Container resource produces the following output properties:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="containerstatus_csharp">
<a href="#containerstatus_csharp" style="color: inherit; text-decoration: inherit;">Container<wbr>Status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Current status of the container.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="createddatetime_csharp">
<a href="#createddatetime_csharp" style="color: inherit; text-decoration: inherit;">Created<wbr>Date<wbr>Time</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The UTC time when container got created.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_csharp">
<a href="#id_csharp" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.{{% /md %}}</dd>
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
        <span id="refreshdetails_csharp">
<a href="#refreshdetails_csharp" style="color: inherit; text-decoration: inherit;">Refresh<wbr>Details</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#refreshdetailsresponse">Pulumi.<wbr>Azure<wbr>Next<wbr>Gen.<wbr>Data<wbr>Box<wbr>Edge.<wbr>Outputs.<wbr>Refresh<wbr>Details<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Details of the refresh job on this container.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_csharp">
<a href="#type_csharp" style="color: inherit; text-decoration: inherit;">Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hierarchical type of the object.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="containerstatus_go">
<a href="#containerstatus_go" style="color: inherit; text-decoration: inherit;">Container<wbr>Status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Current status of the container.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="createddatetime_go">
<a href="#createddatetime_go" style="color: inherit; text-decoration: inherit;">Created<wbr>Date<wbr>Time</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The UTC time when container got created.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_go">
<a href="#id_go" style="color: inherit; text-decoration: inherit;">Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.{{% /md %}}</dd>
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
        <span id="refreshdetails_go">
<a href="#refreshdetails_go" style="color: inherit; text-decoration: inherit;">Refresh<wbr>Details</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#refreshdetailsresponse">Refresh<wbr>Details<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Details of the refresh job on this container.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_go">
<a href="#type_go" style="color: inherit; text-decoration: inherit;">Type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hierarchical type of the object.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="containerstatus_nodejs">
<a href="#containerstatus_nodejs" style="color: inherit; text-decoration: inherit;">container<wbr>Status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Current status of the container.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="createddatetime_nodejs">
<a href="#createddatetime_nodejs" style="color: inherit; text-decoration: inherit;">created<wbr>Date<wbr>Time</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The UTC time when container got created.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_nodejs">
<a href="#id_nodejs" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.{{% /md %}}</dd>
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
        <span id="refreshdetails_nodejs">
<a href="#refreshdetails_nodejs" style="color: inherit; text-decoration: inherit;">refresh<wbr>Details</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#refreshdetailsresponse">Refresh<wbr>Details<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Details of the refresh job on this container.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_nodejs">
<a href="#type_nodejs" style="color: inherit; text-decoration: inherit;">type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The hierarchical type of the object.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="container_status_python">
<a href="#container_status_python" style="color: inherit; text-decoration: inherit;">container_<wbr>status</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Current status of the container.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="created_date_time_python">
<a href="#created_date_time_python" style="color: inherit; text-decoration: inherit;">created_<wbr>date_<wbr>time</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The UTC time when container got created.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="id_python">
<a href="#id_python" style="color: inherit; text-decoration: inherit;">id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.{{% /md %}}</dd>
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
        <span id="refresh_details_python">
<a href="#refresh_details_python" style="color: inherit; text-decoration: inherit;">refresh_<wbr>details</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#refreshdetailsresponse">Refresh<wbr>Details<wbr>Response</a></span>
    </dt>
    <dd>{{% md %}}Details of the refresh job on this container.{{% /md %}}</dd>
    <dt class="property-"
            title="">
        <span id="type_python">
<a href="#type_python" style="color: inherit; text-decoration: inherit;">type</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The hierarchical type of the object.{{% /md %}}</dd>
</dl>
{{% /choosable %}}







## Supporting Types



<h4 id="azurecontainerdataformat">Azure<wbr>Container<wbr>Data<wbr>Format</h4>

{{% choosable language csharp %}}
<dl class="tabular">
    <dt>Block<wbr>Blob</dt>
    <dd>BlockBlob</dd>
    <dt>Page<wbr>Blob</dt>
    <dd>PageBlob</dd>
    <dt>Azure<wbr>File</dt>
    <dd>AzureFile</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="tabular">
    <dt>Azure<wbr>Container<wbr>Data<wbr>Format<wbr>Block<wbr>Blob</dt>
    <dd>BlockBlob</dd>
    <dt>Azure<wbr>Container<wbr>Data<wbr>Format<wbr>Page<wbr>Blob</dt>
    <dd>PageBlob</dd>
    <dt>Azure<wbr>Container<wbr>Data<wbr>Format<wbr>Azure<wbr>File</dt>
    <dd>AzureFile</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="tabular">
    <dt>Block<wbr>Blob</dt>
    <dd>BlockBlob</dd>
    <dt>Page<wbr>Blob</dt>
    <dd>PageBlob</dd>
    <dt>Azure<wbr>File</dt>
    <dd>AzureFile</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="tabular">
    <dt>BLOCK_BLOB</dt>
    <dd>BlockBlob</dd>
    <dt>PAGE_BLOB</dt>
    <dd>PageBlob</dd>
    <dt>AZURE_FILE</dt>
    <dd>AzureFile</dd>
</dl>
{{% /choosable %}}

<h4 id="refreshdetailsresponse">Refresh<wbr>Details<wbr>Response</h4>

{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="errormanifestfile_csharp">
<a href="#errormanifestfile_csharp" style="color: inherit; text-decoration: inherit;">Error<wbr>Manifest<wbr>File</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Indicates the relative path of the error xml for the last refresh job on this particular share or container, if any. This could be a failed job or a successful job.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="inprogressrefreshjobid_csharp">
<a href="#inprogressrefreshjobid_csharp" style="color: inherit; text-decoration: inherit;">In<wbr>Progress<wbr>Refresh<wbr>Job<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}If a refresh job is currently in progress on this share or container, this field indicates the ARM resource ID of that job. The field is empty if no job is in progress.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastcompletedrefreshjobtimeinutc_csharp">
<a href="#lastcompletedrefreshjobtimeinutc_csharp" style="color: inherit; text-decoration: inherit;">Last<wbr>Completed<wbr>Refresh<wbr>Job<wbr>Time<wbr>In<wbr>UTC</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Indicates the completed time for the last refresh job on this particular share or container, if any.This could be a failed job or a successful job.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastjob_csharp">
<a href="#lastjob_csharp" style="color: inherit; text-decoration: inherit;">Last<wbr>Job</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Indicates the id of the last refresh job on this particular share or container,if any. This could be a failed job or a successful job.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="errormanifestfile_go">
<a href="#errormanifestfile_go" style="color: inherit; text-decoration: inherit;">Error<wbr>Manifest<wbr>File</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Indicates the relative path of the error xml for the last refresh job on this particular share or container, if any. This could be a failed job or a successful job.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="inprogressrefreshjobid_go">
<a href="#inprogressrefreshjobid_go" style="color: inherit; text-decoration: inherit;">In<wbr>Progress<wbr>Refresh<wbr>Job<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}If a refresh job is currently in progress on this share or container, this field indicates the ARM resource ID of that job. The field is empty if no job is in progress.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastcompletedrefreshjobtimeinutc_go">
<a href="#lastcompletedrefreshjobtimeinutc_go" style="color: inherit; text-decoration: inherit;">Last<wbr>Completed<wbr>Refresh<wbr>Job<wbr>Time<wbr>In<wbr>UTC</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Indicates the completed time for the last refresh job on this particular share or container, if any.This could be a failed job or a successful job.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastjob_go">
<a href="#lastjob_go" style="color: inherit; text-decoration: inherit;">Last<wbr>Job</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Indicates the id of the last refresh job on this particular share or container,if any. This could be a failed job or a successful job.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="errormanifestfile_nodejs">
<a href="#errormanifestfile_nodejs" style="color: inherit; text-decoration: inherit;">error<wbr>Manifest<wbr>File</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Indicates the relative path of the error xml for the last refresh job on this particular share or container, if any. This could be a failed job or a successful job.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="inprogressrefreshjobid_nodejs">
<a href="#inprogressrefreshjobid_nodejs" style="color: inherit; text-decoration: inherit;">in<wbr>Progress<wbr>Refresh<wbr>Job<wbr>Id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}If a refresh job is currently in progress on this share or container, this field indicates the ARM resource ID of that job. The field is empty if no job is in progress.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastcompletedrefreshjobtimeinutc_nodejs">
<a href="#lastcompletedrefreshjobtimeinutc_nodejs" style="color: inherit; text-decoration: inherit;">last<wbr>Completed<wbr>Refresh<wbr>Job<wbr>Time<wbr>In<wbr>UTC</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Indicates the completed time for the last refresh job on this particular share or container, if any.This could be a failed job or a successful job.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="lastjob_nodejs">
<a href="#lastjob_nodejs" style="color: inherit; text-decoration: inherit;">last<wbr>Job</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Indicates the id of the last refresh job on this particular share or container,if any. This could be a failed job or a successful job.{{% /md %}}</dd>
</dl>
{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span id="error_manifest_file_python">
<a href="#error_manifest_file_python" style="color: inherit; text-decoration: inherit;">error_<wbr>manifest_<wbr>file</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Indicates the relative path of the error xml for the last refresh job on this particular share or container, if any. This could be a failed job or a successful job.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="in_progress_refresh_job_id_python">
<a href="#in_progress_refresh_job_id_python" style="color: inherit; text-decoration: inherit;">in_<wbr>progress_<wbr>refresh_<wbr>job_<wbr>id</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}If a refresh job is currently in progress on this share or container, this field indicates the ARM resource ID of that job. The field is empty if no job is in progress.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="last_completed_refresh_job_time_in_utc_python">
<a href="#last_completed_refresh_job_time_in_utc_python" style="color: inherit; text-decoration: inherit;">last_<wbr>completed_<wbr>refresh_<wbr>job_<wbr>time_<wbr>in_<wbr>utc</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Indicates the completed time for the last refresh job on this particular share or container, if any.This could be a failed job or a successful job.{{% /md %}}</dd>
    <dt class="property-optional"
            title="Optional">
        <span id="last_job_python">
<a href="#last_job_python" style="color: inherit; text-decoration: inherit;">last_<wbr>job</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Indicates the id of the last refresh job on this particular share or container,if any. This could be a failed job or a successful job.{{% /md %}}</dd>
</dl>
{{% /choosable %}}


<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-azure-nextgen">https://github.com/pulumi/pulumi-azure-nextgen</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
</dl>

