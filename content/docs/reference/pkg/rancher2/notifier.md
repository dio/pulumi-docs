
---
title: "Notifier"
block_external_search_index: true
---






## Create a Notifier Resource

{{< chooser language "javascript,typescript,python,go,csharp" / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">new </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/rancher2/#Notifier">Notifier</a></span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">args</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/rancher2/#NotifierArgs">NotifierArgs</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">pulumi.CustomResourceOptions</a></span><span class="p">);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">def </span><span class="nf">Notifier</span><span class="p">(resource_name, opts=None, </span>annotations=None<span class="p">, </span>cluster_id=None<span class="p">, </span>description=None<span class="p">, </span>labels=None<span class="p">, </span>name=None<span class="p">, </span>pagerduty_config=None<span class="p">, </span>send_resolved=None<span class="p">, </span>slack_config=None<span class="p">, </span>smtp_config=None<span class="p">, </span>webhook_config=None<span class="p">, </span>wechat_config=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>NewNotifier<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">pulumi.Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">args</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierArgs">NotifierArgs</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">pulumi.ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#Notifier">Notifier</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Rancher2/Pulumi.Rancher2..Notifier.html">Notifier</a></span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Rancher2/Pulumi.Rancher2.NotifierArgs.html">NotifierArgs</a></span> <span class="nx">args<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resource.</dd>
    <dt class="property-optional" title="Optional">
        <span>args</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The arguments to use to populate this resource's properties.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

#### Resource Arguments




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object>?</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Cluster<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object>?</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pagerduty<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">Notifier<wbr>Pagerduty<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Send<wbr>Resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slack<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">Notifier<wbr>Slack<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Smtp<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">Notifier<wbr>Smtp<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Webhook<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">Notifier<wbr>Webhook<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wechat<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">Notifier<wbr>Wechat<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Cluster<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pagerduty<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">*Notifier<wbr>Pagerduty<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Send<wbr>Resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slack<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">*Notifier<wbr>Slack<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Smtp<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">*Notifier<wbr>Smtp<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Webhook<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">*Notifier<wbr>Webhook<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wechat<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">*Notifier<wbr>Wechat<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}?</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>cluster<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}?</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pagerduty<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">Notifier<wbr>Pagerduty<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>send<wbr>Resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>slack<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">Notifier<wbr>Slack<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>smtp<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">Notifier<wbr>Smtp<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>webhook<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">Notifier<wbr>Webhook<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wechat<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">Notifier<wbr>Wechat<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>cluster_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pagerduty_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">Dict[Notifier<wbr>Pagerduty<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>send_<wbr>resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>slack_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">Dict[Notifier<wbr>Slack<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>smtp_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">Dict[Notifier<wbr>Smtp<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>webhook_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">Dict[Notifier<wbr>Webhook<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wechat_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">Dict[Notifier<wbr>Wechat<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}







## Notifier Output Properties

The following output properties are available:




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object></span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Cluster<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object></span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Pagerduty<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">Notifier<wbr>Pagerduty<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Send<wbr>Resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Slack<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">Notifier<wbr>Slack<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Smtp<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">Notifier<wbr>Smtp<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Webhook<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">Notifier<wbr>Webhook<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Wechat<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">Notifier<wbr>Wechat<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>Annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Cluster<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Pagerduty<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">*Notifier<wbr>Pagerduty<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Send<wbr>Resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Slack<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">*Notifier<wbr>Slack<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Smtp<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">*Notifier<wbr>Smtp<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Webhook<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">*Notifier<wbr>Webhook<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>Wechat<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">*Notifier<wbr>Wechat<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>cluster<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>pagerduty<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">Notifier<wbr>Pagerduty<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>send<wbr>Resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>slack<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">Notifier<wbr>Slack<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>smtp<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">Notifier<wbr>Smtp<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>webhook<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">Notifier<wbr>Webhook<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>wechat<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">Notifier<wbr>Wechat<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-"
            title="">
        <span>annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>cluster_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>pagerduty_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">Dict[Notifier<wbr>Pagerduty<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>send_<wbr>resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>slack_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">Dict[Notifier<wbr>Slack<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>smtp_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">Dict[Notifier<wbr>Smtp<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>webhook_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">Dict[Notifier<wbr>Webhook<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-"
            title="">
        <span>wechat_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">Dict[Notifier<wbr>Wechat<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}








## Look up an Existing Notifier Resource

Get an existing Notifier resource's state with the given name, ID, and optional extra properties used to qualify the lookup.

{{< chooser language "javascript,typescript,python,go,csharp  " / >}}

{{% choosable language nodejs %}}
<div class="highlight"><pre class="chroma"><code class="language-typescript" data-lang="typescript"><span class="k">public static </span><span class="nf">get</span><span class="p">(</span><span class="nx">name</span>: <span class="nx"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/string">string</a></span><span class="p">, </span><span class="nx">id</span>: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#ID">Input&lt;ID&gt;</a></span><span class="p">, </span><span class="nx">state</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/rancher2/#NotifierState">NotifierState</a></span><span class="p">, </span><span class="nx">opts</span>?: <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions">CustomResourceOptions</a></span><span class="p">): </span><span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/rancher2/#Notifier">Notifier</a></span></code></pre></div>
{{% /choosable %}}

{{% choosable language python %}}
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"><span class="k">static </span><span class="nf">get</span><span class="p">(resource_name, id, opts=None, </span>annotations=None<span class="p">, </span>cluster_id=None<span class="p">, </span>description=None<span class="p">, </span>labels=None<span class="p">, </span>name=None<span class="p">, </span>pagerduty_config=None<span class="p">, </span>send_resolved=None<span class="p">, </span>slack_config=None<span class="p">, </span>smtp_config=None<span class="p">, </span>webhook_config=None<span class="p">, </span>wechat_config=None<span class="p">, __props__=None);</span></code></pre></div>
{{% /choosable %}}

{{% choosable language go %}}
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"><span class="k">func </span>GetNotifier<span class="p">(</span><span class="nx">ctx</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#Context">Context</a></span><span class="p">, </span><span class="nx">name</span> <span class="nx"><a href="https://golang.org/pkg/builtin/#string">string</a></span><span class="p">, </span><span class="nx">id</span> <span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#IDInput">IDInput</a></span><span class="p">, </span><span class="nx">state</span> *<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierState">NotifierState</a></span><span class="p">, </span><span class="nx">opts</span> ...<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/go/pulumi?tab=doc#ResourceOption">ResourceOption</a></span><span class="p">) (*<span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#Notifier">Notifier</a></span>, error)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language csharp %}}
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Rancher2/Pulumi.Rancher2..Notifier.html">Notifier</a></span><span class="nf"> Get</span><span class="p">(</span><span class="nx"><a href="https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types">string</a></span> <span class="nx">name<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.Input.html">Input&lt;string&gt;</a></span> <span class="nx">id<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi.Rancher2/Pulumi.Rancher2..NotifierState.html">NotifierState</a></span>? <span class="nx">state<span class="p">, </span><span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.CustomResourceOptions.html">CustomResourceOptions</a></span>? <span class="nx">opts = null<span class="p">)</span></code></pre></div>
{{% /choosable %}}

{{% choosable language nodejs %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language python %}}
<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>resource_name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Optional">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
</dl>
{{% /choosable %}}

{{% choosable language go %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

{{% choosable language csharp %}}

<dl class="resources-properties">
    <dt class="property-required" title="Required">
        <span>name</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The unique name of the resulting resource.</dd>
    <dt class="property-required" title="Required">
        <span>id</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>The <em>unique</em> provider ID of the resource to lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>state</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>Any extra arguments used during the lookup.</dd>
    <dt class="property-optional" title="Optional">
        <span>opts</span>
        <span class="property-indicator"></span>
    </dt>
    <dd>A bag of options that control this resource's behavior.</dd>
</dl>

{{% /choosable %}}

The following state arguments are supported:



{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object>?</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cluster<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary<string, object>?</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pagerduty<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">Notifier<wbr>Pagerduty<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Send<wbr>Resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slack<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">Notifier<wbr>Slack<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Smtp<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">Notifier<wbr>Smtp<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Webhook<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">Notifier<wbr>Webhook<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wechat<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">Notifier<wbr>Wechat<wbr>Config<wbr>Args?</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Cluster<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Description</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]interface{}</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Name</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Pagerduty<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">*Notifier<wbr>Pagerduty<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Send<wbr>Resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Slack<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">*Notifier<wbr>Slack<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Smtp<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">*Notifier<wbr>Smtp<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Webhook<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">*Notifier<wbr>Webhook<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Wechat<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">*Notifier<wbr>Wechat<wbr>Config</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}?</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cluster<wbr>Id</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: any}?</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pagerduty<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">Notifier<wbr>Pagerduty<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>send<wbr>Resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>slack<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">Notifier<wbr>Slack<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>smtp<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">Notifier<wbr>Smtp<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>webhook<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">Notifier<wbr>Webhook<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wechat<wbr>Config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">Notifier<wbr>Wechat<wbr>Config?</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>annotations</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}Annotations for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>cluster_<wbr>id</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The cluster id where create notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>description</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The notifier description (string)
* `send_resolved` = (Optional) Enable the notifier to send resolved notifications. Default `false` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>labels</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dict[str, Any]</span>
    </dt>
    <dd>{{% md %}}Labels for notifier object (map)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>name</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}The name of the notifier (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>pagerduty_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierpagerdutyconfig">Dict[Notifier<wbr>Pagerduty<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Pagerduty config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>send_<wbr>resolved</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}Notifier send resolved
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>slack_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierslackconfig">Dict[Notifier<wbr>Slack<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Slack config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>smtp_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifiersmtpconfig">Dict[Notifier<wbr>Smtp<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}SMTP config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>webhook_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwebhookconfig">Dict[Notifier<wbr>Webhook<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Webhook config for notifier (list maxitems:1)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>wechat_<wbr>config</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#notifierwechatconfig">Dict[Notifier<wbr>Wechat<wbr>Config]</a></span>
    </dt>
    <dd>{{% md %}}Wechat config for notifier (list maxitems:1)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}










## Supporting Types

<h4>Notifier<wbr>Pagerduty<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/rancher2/types/input/#NotifierPagerdutyConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/rancher2/types/output/#NotifierPagerdutyConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierPagerdutyConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierPagerdutyConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Service<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Pagerduty service key (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Service<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Pagerduty service key (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>service<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Pagerduty service key (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>service<wbr>Key</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Pagerduty service key (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Notifier<wbr>Slack<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/rancher2/types/input/#NotifierSlackConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/rancher2/types/output/#NotifierSlackConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierSlackConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierSlackConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Webhook url (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Webhook url (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Webhook url (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Webhook url (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Notifier<wbr>Smtp<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/rancher2/types/input/#NotifierSmtpConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/rancher2/types/output/#NotifierSmtpConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierSmtpConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierSmtpConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}SMTP host (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}SMTP password (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}SMTP port (int)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Sender</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}SMTP sender (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tls</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool?</span>
    </dt>
    <dd>{{% md %}}SMTP tls. Default `true` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Username</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}SMTP username (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}SMTP host (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Password</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}SMTP password (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Port</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>{{% md %}}SMTP port (int)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Sender</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}SMTP sender (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Tls</span>
        <span class="property-indicator"></span>
        <span class="property-type">*bool</span>
    </dt>
    <dd>{{% md %}}SMTP tls. Default `true` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Username</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}SMTP username (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}SMTP host (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}SMTP password (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>port</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>{{% md %}}SMTP port (int)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>sender</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}SMTP sender (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tls</span>
        <span class="property-indicator"></span>
        <span class="property-type">boolean?</span>
    </dt>
    <dd>{{% md %}}SMTP tls. Default `true` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>username</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}SMTP username (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>host</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}SMTP host (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>password</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}SMTP password (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>port</span>
        <span class="property-indicator"></span>
        <span class="property-type">float</span>
    </dt>
    <dd>{{% md %}}SMTP port (int)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>sender</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}SMTP sender (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>tls</span>
        <span class="property-indicator"></span>
        <span class="property-type">bool</span>
    </dt>
    <dd>{{% md %}}SMTP tls. Default `true` (bool)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>username</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}SMTP username (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Notifier<wbr>Webhook<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/rancher2/types/input/#NotifierWebhookConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/rancher2/types/output/#NotifierWebhookConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierWebhookConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierWebhookConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Webhook url (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Webhook url (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Webhook url (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-optional"
            title="Optional">
        <span>proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Webhook url (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}





<h4>Notifier<wbr>Wechat<wbr>Config</h4>
{{% choosable language nodejs %}}
> See the <a href="/docs/reference/pkg/nodejs/pulumi/rancher2/types/input/#NotifierWechatConfig">input</a> and <a href="/docs/reference/pkg/nodejs/pulumi/rancher2/types/output/#NotifierWechatConfig">output</a> API doc for this type.
{{% /choosable %}}

{{% choosable language go %}}
> See the <a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierWechatConfigArgs">input</a> and <a href="https://pkg.go.dev/github.com/pulumi/pulumi-rancher2/sdk/go/rancher2/?tab=doc#NotifierWechatConfigOutput">output</a> API doc for this type.
{{% /choosable %}}




{{% choosable language csharp %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Agent</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat agent ID (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Corp</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat corporation ID (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Recipient<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Wechat recipient type. Allowed values: `party` | `tag` | `user` (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Secret</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat agent ID (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language go %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>Agent</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat agent ID (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Corp</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat corporation ID (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>Recipient<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">*string</span>
    </dt>
    <dd>{{% md %}}Wechat recipient type. Allowed values: `party` | `tag` | `user` (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>Secret</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat agent ID (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language nodejs %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>agent</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat agent ID (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>corp</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat corporation ID (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>recipient<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">string?</span>
    </dt>
    <dd>{{% md %}}Wechat recipient type. Allowed values: `party` | `tag` | `user` (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>secret</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>{{% md %}}Wechat agent ID (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}


{{% choosable language python %}}
<dl class="resources-properties">

    <dt class="property-required"
            title="Required">
        <span>agent</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat agent ID (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>corp</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat corporation ID (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>default<wbr>Recipient</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat default recipient (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>proxy<wbr>Url</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat proxy url (string)
{{% /md %}}</dd>

    <dt class="property-optional"
            title="Optional">
        <span>recipient<wbr>Type</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat recipient type. Allowed values: `party` | `tag` | `user` (string)
{{% /md %}}</dd>

    <dt class="property-required"
            title="Required">
        <span>secret</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>{{% md %}}Wechat agent ID (string)
{{% /md %}}</dd>

</dl>
{{% /choosable %}}









<h3>Package Details</h3>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-rancher2">https://github.com/pulumi/pulumi-rancher2</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
    
</dl>
