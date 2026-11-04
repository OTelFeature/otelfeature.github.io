---
layout: default
---
{% assign utm = "utm_source=kubecon-na-2026&utm_medium=qr&utm_campaign=otelfeature" %}

<div class="hero" markdown="1">

![OTelFeature](assets/logo.png)
{: .mark}

KubeCon + CloudNativeCon North America 2026
{: .event}

# {{ site.talk_title }}

Controlling OpenTelemetry instrumentation at runtime with OpenFeature.

[![Flagsmith](assets/logos/flagsmith-white.svg)](https://www.flagsmith.com/?{{ utm }}&utm_content=hero) × [![Dash0](assets/logos/dash0-white.svg)](https://www.dash0.com/?{{ utm }}&utm_content=hero)
{: .partners}

{% if site.slides_url %}[Get the slides]({{ site.slides_url }}){: .button} {% endif %}[Try the PoC on GitHub](https://github.com/OTelFeature/poc){: .button{% if site.slides_url %} .secondary{% endif %}}
{: .actions}

</div>

<div class="callout" markdown="1">

{% if site.recording_url %}**Missed a part?** [Watch the recording]({{ site.recording_url }}).{% else %}**Missed a part?** KubeCon recordings go up on the [CNCF YouTube channel](https://www.youtube.com/@cncf) a few weeks after the event.{% endif %}

</div>

## Talk to us

Questions we didn't get to, want to try this in your own setup, or have opinions on the open questions? Reach out:

- [Open an issue on the poc repo](https://github.com/OTelFeature/poc/issues/new)
- Find us on the [CNCF Slack](https://slack.cncf.io) in `#openfeature` and `#opentelemetry`
- Through our websites: [Simon](https://schrottner.at) and [Juliano](https://jcosta.dev)

## About the talk

Observability is usually configured up front: too much telemetry while everything is healthy, too little once an incident starts. This talk uses OpenFeature flags to control OpenTelemetry instrumentation at runtime, so a service moves from lightweight tracing to detailed diagnostics without a redeploy.

The demo turns tracing off with one flag, drops INTERNAL spans while keeping the I/O edges, and targets by OpenTelemetry semantic conventions used as evaluation context, down to sampling that follows the error rate. The question we leave you with: should semantic conventions become the vendor-neutral control surface for this?

## Speakers

<div class="people" markdown="1">

<div class="person" markdown="1">

![Simon Schrottner](https://github.com/aepfli.png?size=400)

### Simon Schrottner

Flagsmith · OpenFeature Technical Committee

- [Website](https://schrottner.at)
- [GitHub](https://github.com/aepfli)
{: .social}

</div>

<div class="person" markdown="1">

![Juliano Costa](https://github.com/julianocosta89.png?size=400)

### Juliano Costa

Dash0 · OpenTelemetry Demo maintainer

- [Website](https://jcosta.dev)
- [GitHub](https://github.com/julianocosta89)
{: .social}

</div>

</div>

## The code

The project behind the talk is called **OTelFeature**:

- [poc](https://github.com/OTelFeature/poc) — the demo from the talk
- [otelfeature-instrument](https://github.com/OTelFeature/otelfeature-instrument) — zero-code OpenTelemetry launcher with flagd-controlled span suppression
- [otelfeature-java-extension](https://github.com/OTelFeature/otelfeature-java-extension) — the Java agent counterpart

Found it useful? A star on the repos tells us to keep going.

## Take it further

<div class="offers" markdown="1">

<div class="offer" markdown="1">

[![Flagsmith](assets/logos/flagsmith.svg)](https://www.flagsmith.com/?{{ utm }}&utm_content=offer)
{: .company}

Open-source feature flag service with OpenFeature providers for Java, Python, Go and more, a dashboard and segments for targeting.

[Start free](https://app.flagsmith.com/signup/?{{ utm }}&utm_content=offer){: .button} [OpenFeature docs](https://docs.flagsmith.com/integrating-with-flagsmith/openfeature?{{ utm }}&utm_content=offer)

</div>

<div class="offer" markdown="1">

[![Dash0](assets/logos/dash0.svg)](https://www.dash0.com/?{{ utm }}&utm_content=offer)
{: .company}

OpenTelemetry-native observability. See the effect of your flags on your traces.

[Start free trial](https://www.dash0.com/sign-up?{{ utm }}&utm_content=offer){: .button} [Book a demo](https://www.dash0.com/book-a-demo?{{ utm }}&utm_content=offer)

</div>

</div>

## Learn more

- [![](assets/logos/openfeature.svg) OpenFeature](https://openfeature.dev)
- [![](assets/logos/flagd.svg) flagd](https://flagd.dev)
- [![](assets/logos/opentelemetry.svg) OpenTelemetry](https://opentelemetry.io)
- [![](assets/logos/flagsmith-icon.svg) Flagsmith](https://www.flagsmith.com/?{{ utm }}&utm_content=learn-more)
- [![](assets/logos/dash0-icon.svg) Dash0](https://www.dash0.com/?{{ utm }}&utm_content=learn-more)
{: .tech}

{% if site.session_url %}
[How was the talk? Rate the session]({{ site.session_url }})
{: .feedback}
{% endif %}
