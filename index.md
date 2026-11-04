---
layout: default
---
{% assign utm = "utm_source=kubecon-na-2026&utm_medium=qr&utm_campaign=otelfeature" %}

<div class="hero" markdown="1">

KubeCon + CloudNativeCon North America 2026
{: .event}

# OTelFeature

Controlling OpenTelemetry instrumentation at runtime with OpenFeature and flagd.

[![Flagsmith](assets/logos/flagsmith-white.svg)](https://www.flagsmith.com/?{{ utm }}&utm_content=hero) × [![Dash0](assets/logos/dash0-white.svg)](https://www.dash0.com/?{{ utm }}&utm_content=hero)
{: .partners}

{% if site.slides_url %}[Get the slides]({{ site.slides_url }}){: .button} {% endif %}[Try the PoC on GitHub](https://github.com/OTelFeature/poc){: .button{% if site.slides_url %} .secondary{% endif %}}

</div>

{% if site.recording_signup_url %}
<div class="callout" markdown="1">

**The recording isn't out yet.** [Get an email when it is]({{ site.recording_signup_url }}), together with the slides and the follow-ups from Q&A.

</div>
{% endif %}

{% if site.booths.flagsmith or site.booths.dash0 %}
## Find us at KubeCon

Want to see the demo with your own stack, or argue about the open questions? Come by:

{% if site.booths.flagsmith %}- **Flagsmith**: {{ site.booths.flagsmith }}
{% endif %}{% if site.booths.dash0 %}- **Dash0**: {{ site.booths.dash0 }}
{% endif %}
{% endif %}

## Speakers

<div class="people" markdown="1">

<div class="person" markdown="1">

![Simon Schrottner](https://github.com/aepfli.png?size=400)

### Simon Schrottner

[![Flagsmith](assets/logos/flagsmith.svg)](https://www.flagsmith.com/?{{ utm }}&utm_content=speaker)
{: .company}

OpenFeature Technical Committee

- [GitHub](https://github.com/aepfli)
{: .social}

</div>

<div class="person" markdown="1">

![Juliano Costa](https://github.com/julianocosta89.png?size=400)

### Juliano Costa

[![Dash0](assets/logos/dash0.svg)](https://www.dash0.com/?{{ utm }}&utm_content=speaker)
{: .company}

- [GitHub](https://github.com/julianocosta89)
{: .social}

</div>

</div>

## Take it further

<div class="offers" markdown="1">

<div class="offer" markdown="1">

[![Flagsmith](assets/logos/flagsmith.svg)](https://www.flagsmith.com/?{{ utm }}&utm_content=offer)
{: .company}

Open-source feature flags with OpenFeature providers for Java, Python, Go and more. Manage flags like the ones in this talk from a dashboard, with segments for targeting.

[Start free](https://app.flagsmith.com/signup?{{ utm }}&utm_content=offer){: .button} [OpenFeature docs](https://docs.flagsmith.com/integrating-with-flagsmith/openfeature?{{ utm }}&utm_content=offer)

</div>

<div class="offer" markdown="1">

[![Dash0](assets/logos/dash0.svg)](https://www.dash0.com/?{{ utm }}&utm_content=offer)
{: .company}

OpenTelemetry-native observability. See what your flags did to your traces: fewer spans, the same answers.

[Start free trial](https://www.dash0.com/sign-up?{{ utm }}&utm_content=offer){: .button} [Book a demo](https://www.dash0.com/book-a-demo?{{ utm }}&utm_content=offer)

</div>

</div>

## The code

- [poc](https://github.com/OTelFeature/poc) — the demo from the talk
- [otelfeature-instrument](https://github.com/OTelFeature/otelfeature-instrument) — zero-code OpenTelemetry launcher with flagd-controlled span suppression
- [otelfeature-java-extension](https://github.com/OTelFeature/otelfeature-java-extension) — the Java agent counterpart

Found it useful? A star on the repos tells us to keep going.

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
