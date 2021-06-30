---
title: "First_post"
date: 2021-06-17T01:26:34+07:00
draft: false
---

WARN 2021/06/17 01:26:16 found no layout file for "JSON" for kind "home": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
Total in 14 ms

{{< highlight html >}}
<section id="main">
    <div>
        <h1 id="title">{{ .Title }}</h1>
        {{ range .Pages }}
            {{ .Render "summary"}}
        {{ end }}
    </div>
</section>
{{< /highlight >}}


{{< highlight html >}}
<section id="main">
    <div>
        <h1 id="title">{{ .Title }}</h1>
        {{ range .Pages }}
            {{ .Render "summary"}}
        {{ end }}
    </div>
</section>
{{< /highlight >}}

