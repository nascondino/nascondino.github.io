---
layout: page
title: RESI Informatica S.p.A.
vat: "05633751002"
products:
- GEMINI-NET
categories:
- Wiretapping
- IP Network Surveillance
- Deep Packet Inspection (DPI)
- SS7/SIGTRAN Network Surveillance
---

**VAT Number:** {{ page.vat }}.  
**Product Names:** {% for p in page.products %}{{ p }}{% unless forloop.last %}, {% endunless %}{% endfor %}.  
**[Capabilities](/capabilities/):** {% for c in page.categories %}{{ c }}{% unless forloop.last %}, {% endunless %}{% endfor %}.  
**Parent Company:** *Resi Group S.p.A. (01353620592)*.

<!-- more -->

**RESI Informatica** is an italian information technology company.  
Founded in 1998, **RESI Informatica** is part of **Resi Group** alongside with **[IPS](/companies/ips.html)**.

In February 2010, RESI got authorization to sell a demo of **[Hacking Team](/companies/hackingteam.html)**'s software to ATI, a Tunisian government agency which controls the country's biggest Internet Service Provider.[[1](#external-references)][[2](#external-references)]

In May 2022, TIM's *"Red Team"* discovered 2 vulnerabilities (one Critical and one Medium severity) in the **RESI**'s **GEMINI-NET** platform.[[3](#external-references)][[4](#external-references)]

## External References
1. [vice.com](https://www.vice.com/en/article/kbzj4z/meet-the-companies-that-helped-hacking-team-sell-tools-to-repressive-governments)
2. [web.archive.org - lastampa.it](https://web.archive.org/web/20160416230611/http://www.lastampa.it/2015/08/07/tecnologia/the-italian-job-hacking-team-e-le-collaborazioni-con-le-aziende-tricolori-TLlsvbByHLsBnP68CWOh0H/pagina.html)
3. [CVE-2022-29538](https://nvd.nist.gov/vuln/detail/CVE-2022-29538)
4. [CVE-2022-29539](https://nvd.nist.gov/vuln/detail/CVE-2022-29539)

