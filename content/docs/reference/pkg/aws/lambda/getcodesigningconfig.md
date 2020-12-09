
---
title: "GetCodeSigningConfig"
title_tag: "Function GetCodeSigningConfig | Module lambda | Package AWS"
meta_desc: "Explore the GetCodeSigningConfig function of the lambda module, including examples, input properties, output properties, and supporting types. Provides information about a Lambda Code Signing Config. A code signing configuration defines a list of allowed signing profiles and defines the code-signing validation policy (action to be taken if deployment validation checks fail)."
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

Provides information about a Lambda Code Signing Config. A code signing configuration defines a list of allowed signing profiles and defines the code-signing validation policy (action to be taken if deployment validation checks fail).

For information about Lambda code signing configurations and how to use them, see [configuring code signing for Lambda functions](https://docs.aws.amazon.com/lambda/latest/dg/configuration-codesigning.html)


{{% examples %}}
## Example Usage

{{< chooser language "typescript,python,go,csharp" / >}}

{{% example csharp %}}
```csharp
using Pulumi;
using Aws = Pulumi.Aws;

class MyStack : Stack
{
    public MyStack()
    {
        var existingCsc = Output.Create(Aws.Lambda.GetCodeSigningConfig.InvokeAsync(new Aws.Lambda.GetCodeSigningConfigArgs
        {
            Arn = $"arn:aws:lambda:{@var.Aws_region}:{@var.Aws_account}:code-signing-config:csc-0f6c334abcdea4d8b",
        }));
    }

}
```

{{% /example %}}

{{% example go %}}
```go
package main

import (
	"fmt"

	"github.com/pulumi/pulumi-aws/sdk/v3/go/aws/lambda"
	"github.com/pulumi/pulumi/sdk/v2/go/pulumi"
)

func main() {
	pulumi.Run(func(ctx *pulumi.Context) error {
		_, err := lambda.LookupCodeSigningConfig(ctx, &lambda.LookupCodeSigningConfigArgs{
			Arn: fmt.Sprintf("%v%v%v%v%v", "arn:aws:lambda:", _var.Aws_region, ":", _var.Aws_account, ":code-signing-config:csc-0f6c334abcdea4d8b"),
		}, nil)
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
import pulumi_aws as aws

existing_csc = aws.lambda.get_code_signing_config(arn=f"arn:aws:lambda:{var['aws_region']}:{var['aws_account']}:code-signing-config:csc-0f6c334abcdea4d8b")
```

{{% /example %}}

{{% example typescript %}}

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as aws from "@pulumi/aws";

const existingCsc = pulumi.output(aws.lambda.getCodeSigningConfig({
    arn: `arn:aws:lambda:${var_aws_region}:${var_aws_account}:code-signing-config:csc-0f6c334abcdea4d8b`,
}, { async: true }));
```

{{% /example %}}

{{% /examples %}}


## Using GetCodeSigningConfig {#using}

{{< chooser language "typescript,python,go,csharp" / >}}


{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">function </span>getCodeSigningConfig<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/aws/lambda/#GetCodeSigningConfigArgs">GetCodeSigningConfigArgs</a></span><span class="p">, </span><span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/aws/lambda/#GetCodeSigningConfigResult">GetCodeSigningConfigResult</a></span>></span></code></pre></div>
{{% /choosable %}}


{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span>get_code_signing_config(</span><span class="nx">arn</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">, </span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> GetCodeSigningConfigResult</code></pre></div>
{{% /choosable %}}


{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>LookupCodeSigningConfig<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">args</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-aws/sdk/v3/go/aws/lambda?tab=doc#LookupCodeSigningConfigArgs">LookupCodeSigningConfigArgs</a></span><span class="p">, </span><span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v2/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-aws/sdk/v3/go/aws/lambda?tab=doc#LookupCodeSigningConfigResult">LookupCodeSigningConfigResult</a></span>, error)</span></code></pre></div>

> Note: This function is named `LookupCodeSigningConfig` in the Go SDK.

{{% /choosable %}}


{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetCodeSigningConfig </span><span class="p">{</span><span class="k">
    public static </span>Task&lt;<span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Aws/Pulumi.Aws.Lambda.GetCodeSigningConfigResult.html">GetCodeSigningConfigResult</a></span>> <span class="p">InvokeAsync(</span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Aws/Pulumi.Aws.Lambda.GetCodeSigningConfigArgs.html">GetCodeSigningConfigArgs</a></span><span class="p"> </span><span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
{{% /choosable %}}



The following arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="arn_csharp">
<a href="#arn_csharp" style="color: inherit; text-decoration: inherit;">Arn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The Amazon Resource Name (ARN) of the code signing configuration.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="arn_go">
<a href="#arn_go" style="color: inherit; text-decoration: inherit;">Arn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The Amazon Resource Name (ARN) of the code signing configuration.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="arn_nodejs">
<a href="#arn_nodejs" style="color: inherit; text-decoration: inherit;">arn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The Amazon Resource Name (ARN) of the code signing configuration.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="arn_python">
<a href="#arn_python" style="color: inherit; text-decoration: inherit;">arn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The Amazon Resource Name (ARN) of the code signing configuration.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## GetCodeSigningConfig Result {#result}

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="allowedpublishers_csharp">
<a href="#allowedpublishers_csharp" style="color: inherit; text-decoration: inherit;">Allowed<wbr>Publishers</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getcodesigningconfigallowedpublisher">List&lt;Get<wbr>Code<wbr>Signing<wbr>Config<wbr>Allowed<wbr>Publisher&gt;</a></span>
    </dt>
    <dd>{{% md %}}List of allowed publishers as signing profiles for this code signing configuration.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="arn_csharp">
<a href="#arn_csharp" style="color: inherit; text-decoration: inherit;">Arn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="configid_csharp">
<a href="#configid_csharp" style="color: inherit; text-decoration: inherit;">Config<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Unique identifier for the code signing configuration.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="description_csharp">
<a href="#description_csharp" style="color: inherit; text-decoration: inherit;">Description</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Code signing configuration description.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="id_csharp">
<a href="#id_csharp" style="color: inherit; text-decoration: inherit;">Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="lastmodified_csharp">
<a href="#lastmodified_csharp" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}The date and time that the code signing configuration was last modified.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="policies_csharp">
<a href="#policies_csharp" style="color: inherit; text-decoration: inherit;">Policies</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getcodesigningconfigpolicy">List&lt;Get<wbr>Code<wbr>Signing<wbr>Config<wbr>Policy&gt;</a></span>
    </dt>
    <dd>{{% md %}}List of code signing policies that control the validation failure action for signature mismatch or expiry.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="allowedpublishers_go">
<a href="#allowedpublishers_go" style="color: inherit; text-decoration: inherit;">Allowed<wbr>Publishers</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getcodesigningconfigallowedpublisher">[]Get<wbr>Code<wbr>Signing<wbr>Config<wbr>Allowed<wbr>Publisher</a></span>
    </dt>
    <dd>{{% md %}}List of allowed publishers as signing profiles for this code signing configuration.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="arn_go">
<a href="#arn_go" style="color: inherit; text-decoration: inherit;">Arn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="configid_go">
<a href="#configid_go" style="color: inherit; text-decoration: inherit;">Config<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Unique identifier for the code signing configuration.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="description_go">
<a href="#description_go" style="color: inherit; text-decoration: inherit;">Description</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Code signing configuration description.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="id_go">
<a href="#id_go" style="color: inherit; text-decoration: inherit;">Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="lastmodified_go">
<a href="#lastmodified_go" style="color: inherit; text-decoration: inherit;">Last<wbr>Modified</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}The date and time that the code signing configuration was last modified.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="policies_go">
<a href="#policies_go" style="color: inherit; text-decoration: inherit;">Policies</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getcodesigningconfigpolicy">[]Get<wbr>Code<wbr>Signing<wbr>Config<wbr>Policy</a></span>
    </dt>
    <dd>{{% md %}}List of code signing policies that control the validation failure action for signature mismatch or expiry.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="allowedpublishers_nodejs">
<a href="#allowedpublishers_nodejs" style="color: inherit; text-decoration: inherit;">allowed<wbr>Publishers</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getcodesigningconfigallowedpublisher">Get<wbr>Code<wbr>Signing<wbr>Config<wbr>Allowed<wbr>Publisher[]</a></span>
    </dt>
    <dd>{{% md %}}List of allowed publishers as signing profiles for this code signing configuration.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="arn_nodejs">
<a href="#arn_nodejs" style="color: inherit; text-decoration: inherit;">arn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="configid_nodejs">
<a href="#configid_nodejs" style="color: inherit; text-decoration: inherit;">config<wbr>Id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Unique identifier for the code signing configuration.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="description_nodejs">
<a href="#description_nodejs" style="color: inherit; text-decoration: inherit;">description</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Code signing configuration description.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="id_nodejs">
<a href="#id_nodejs" style="color: inherit; text-decoration: inherit;">id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="lastmodified_nodejs">
<a href="#lastmodified_nodejs" style="color: inherit; text-decoration: inherit;">last<wbr>Modified</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}The date and time that the code signing configuration was last modified.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="policies_nodejs">
<a href="#policies_nodejs" style="color: inherit; text-decoration: inherit;">policies</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getcodesigningconfigpolicy">Get<wbr>Code<wbr>Signing<wbr>Config<wbr>Policy[]</a></span>
    </dt>
    <dd>{{% md %}}List of code signing policies that control the validation failure action for signature mismatch or expiry.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span id="allowed_publishers_python">
<a href="#allowed_publishers_python" style="color: inherit; text-decoration: inherit;">allowed_<wbr>publishers</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getcodesigningconfigallowedpublisher">Get<wbr>Code<wbr>Signing<wbr>Config<wbr>Allowed<wbr>Publisher]</a></span>
    </dt>
    <dd>{{% md %}}List of allowed publishers as signing profiles for this code signing configuration.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="arn_python">
<a href="#arn_python" style="color: inherit; text-decoration: inherit;">arn</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="config_id_python">
<a href="#config_id_python" style="color: inherit; text-decoration: inherit;">config_<wbr>id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Unique identifier for the code signing configuration.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="description_python">
<a href="#description_python" style="color: inherit; text-decoration: inherit;">description</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Code signing configuration description.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="id_python">
<a href="#id_python" style="color: inherit; text-decoration: inherit;">id</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The provider-assigned unique ID for this managed resource.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="last_modified_python">
<a href="#last_modified_python" style="color: inherit; text-decoration: inherit;">last_<wbr>modified</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}The date and time that the code signing configuration was last modified.
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span id="policies_python">
<a href="#policies_python" style="color: inherit; text-decoration: inherit;">policies</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#getcodesigningconfigpolicy">Get<wbr>Code<wbr>Signing<wbr>Config<wbr>Policy]</a></span>
    </dt>
    <dd>{{% md %}}List of code signing policies that control the validation failure action for signature mismatch or expiry.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Supporting Types


<h4 id="getcodesigningconfigallowedpublisher">Get<wbr>Code<wbr>Signing<wbr>Config<wbr>Allowed<wbr>Publisher</h4>
{{% choosable language nodejs %}}
> See the   <a href="/docs/reference/pkg/nodejs/pulumi/aws/types/output/#GetCodeSigningConfigAllowedPublisher">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the   <a href="https://pkg.go.dev/github.com/pulumi/pulumi-aws/sdk/v3/go/aws/lambda?tab=doc#GetCodeSigningConfigAllowedPublisher">output</a> API doc for this type.
{{% /choosable %}}
{{% choosable language csharp %}}
> See the   <a href="/docs/reference/pkg/dotnet/Pulumi.Aws/Pulumi.Aws.Lambda.Outputs.GetCodeSigningConfigAllowedPublisher.html">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="signingprofileversionarns_csharp">
<a href="#signingprofileversionarns_csharp" style="color: inherit; text-decoration: inherit;">Signing<wbr>Profile<wbr>Version<wbr>Arns</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">List&lt;string&gt;</a></span>
    </dt>
    <dd>{{% md %}}The Amazon Resource Name (ARN) for each of the signing profiles. A signing profile defines a trusted user who can sign a code package.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="signingprofileversionarns_go">
<a href="#signingprofileversionarns_go" style="color: inherit; text-decoration: inherit;">Signing<wbr>Profile<wbr>Version<wbr>Arns</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">[]string</a></span>
    </dt>
    <dd>{{% md %}}The Amazon Resource Name (ARN) for each of the signing profiles. A signing profile defines a trusted user who can sign a code package.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="signingprofileversionarns_nodejs">
<a href="#signingprofileversionarns_nodejs" style="color: inherit; text-decoration: inherit;">signing<wbr>Profile<wbr>Version<wbr>Arns</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string[]</a></span>
    </dt>
    <dd>{{% md %}}The Amazon Resource Name (ARN) for each of the signing profiles. A signing profile defines a trusted user who can sign a code package.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="signing_profile_version_arns_python">
<a href="#signing_profile_version_arns_python" style="color: inherit; text-decoration: inherit;">signing_<wbr>profile_<wbr>version_<wbr>arns</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">Sequence[str]</a></span>
    </dt>
    <dd>{{% md %}}The Amazon Resource Name (ARN) for each of the signing profiles. A signing profile defines a trusted user who can sign a code package.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4 id="getcodesigningconfigpolicy">Get<wbr>Code<wbr>Signing<wbr>Config<wbr>Policy</h4>
{{% choosable language nodejs %}}
> See the   <a href="/docs/reference/pkg/nodejs/pulumi/aws/types/output/#GetCodeSigningConfigPolicy">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the   <a href="https://pkg.go.dev/github.com/pulumi/pulumi-aws/sdk/v3/go/aws/lambda?tab=doc#GetCodeSigningConfigPolicy">output</a> API doc for this type.
{{% /choosable %}}
{{% choosable language csharp %}}
> See the   <a href="/docs/reference/pkg/dotnet/Pulumi.Aws/Pulumi.Aws.Lambda.Outputs.GetCodeSigningConfigPolicy.html">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="untrustedartifactondeployment_csharp">
<a href="#untrustedartifactondeployment_csharp" style="color: inherit; text-decoration: inherit;">Untrusted<wbr>Artifact<wbr>On<wbr>Deployment</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span>
    </dt>
    <dd>{{% md %}}Code signing configuration policy for deployment validation failure.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="untrustedartifactondeployment_go">
<a href="#untrustedartifactondeployment_go" style="color: inherit; text-decoration: inherit;">Untrusted<wbr>Artifact<wbr>On<wbr>Deployment</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://golang.org/pkg/builtin/#string">string</a></span>
    </dt>
    <dd>{{% md %}}Code signing configuration policy for deployment validation failure.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="untrustedartifactondeployment_nodejs">
<a href="#untrustedartifactondeployment_nodejs" style="color: inherit; text-decoration: inherit;">untrusted<wbr>Artifact<wbr>On<wbr>Deployment</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span>
    </dt>
    <dd>{{% md %}}Code signing configuration policy for deployment validation failure.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span id="untrusted_artifact_on_deployment_python">
<a href="#untrusted_artifact_on_deployment_python" style="color: inherit; text-decoration: inherit;">untrusted_<wbr>artifact_<wbr>on_<wbr>deployment</a>
</span> 
        <span class="property-indicator"></span>
        <span class="property-type"><a href="https://docs.python.org/3/library/stdtypes.html">str</a></span>
    </dt>
    <dd>{{% md %}}Code signing configuration policy for deployment validation failure.
{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-aws">https://github.com/pulumi/pulumi-aws</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
	<dt>Notes</dt>
	<dd>This Pulumi package is based on the [`aws` Terraform Provider](https://github.com/terraform-providers/terraform-provider-aws).</dd>
</dl>
