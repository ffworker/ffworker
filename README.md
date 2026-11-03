<div align="center">

# Dennis Kappel

**System Administrator · Linux · Infrastructure · Networking**

I like knowing why a system works — and why it stopped working.

[CV](https://cv.bytegeist.dev) · [Self-assessed skills](https://cv.bytegeist.dev/skills.html) · [Bytegeist Blog](https://blog.bytegeist.dev/) · [Repositories](https://github.com/ffworker?tab=repositories)

</div>

---

### What I work with

`Linux` · `Bash` · `Docker / Compose` · `Proxmox` · `Networking` · `NetBird / VPN` · `Kubernetes / Talos (lab)` · `GitHub Actions` · `NFS / SMB` · `Prometheus / Grafana`

I work best when I can understand the whole path: host → network → service → user. I use documentation, search and AI where they make me faster, but I don't treat generated output as understanding. If I can't reason about a change yet, it belongs in a lab first.

### Selected work

<table>
<tr>
<td colspan="2" valign="top">

#### [Signaturee ↗](https://signaturee.bytegeist.dev/)

**Windows — available and used in a workplace setting (maintainer-reported):** a self-hosted browser workflow for IT-managed and employee self-service signatures, using existing templates and Active Directory. Employee lookup, preflight, preview and targeted runs of up to 50 users reduce repeated manual setup. LibreOffice provides RTF conversion; generated Classic Outlook files are not native new Outlook/web deployment. The public project is separate from the workplace installation, whose exact installed release is not independently verified.

**Linux — experimental:** an independently developed Docker-first edition with offline generation, CLI workflows and a limited development UI. Real LDAP acceptance and the full authenticated UI remain pending.

[Explore Signaturee ↗](https://signaturee.bytegeist.dev/) · [Windows v2.0.1 release ↗](https://github.com/ffworker/signaturee-win/releases/tag/v2.0.1) · [The story ↗](https://blog.bytegeist.dev/artikel/signaturee/)

**PowerShell · Node.js · Active Directory · LibreOffice · IT workflows**

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### [RSS2Slideshow ↗](https://github.com/ffworker/rss2slideshow)

A small, self-hosted RSS news display with a web editor for feeds and design. Docker/Compose, optional article images and QR codes, and local branding/settings that survive code updates. Built as a **personal hobby project in my spare time, outside working hours**; real-world display feedback helped shape the final release.

[Read the story ↗](https://blog.bytegeist.dev/artikel/rss2slideshow/) · [Source ↗](https://github.com/ffworker/rss2slideshow)

**Python · Flask · Docker Compose · RSS · Digital Signage**

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### [CKA Lab ↗](https://github.com/ffworker/cka-lab)

A Kubernetes learning experiment: eight break/fix missions, real-state validators, and an optional AI tutor designed to give hints rather than solve the task. The learning loop is being re-evaluated before claiming practical outcomes.

**Kubernetes · Troubleshooting · Learning by doing**

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### [Bytegeist Docs ↗](https://github.com/ffworker/bytegeist-docs)

**The problem:** documentation scattered across project READMEs and docs folders. A successful bulk importer was not the same as a useful personal reference.

**The current direction:** I retired the old VPS02 **deployment pipeline** (the former runtime still awaits a safe decommission) and started a clean, curated **Zensical v2**. Each repository stays the source of truth; only explicitly selected README/docs files **will be** collected into a future private reading copy. The interface gets a Bytegeist visual identity, and selected source revisions are recorded.

**Status:** reproducible local Zensical preview and opt-in source collector are build-tested in CI. **No v2 production deployment or independently accepted private endpoint yet.** The previous MkDocs/GitHub Actions/NetBird implementation remains in the Git history as a practical learning stage, not the current hosting claim.

[Read the complete story ↗](https://blog.bytegeist.dev/artikel/bytegeist-docs/) · [Inspect Zensical v2 ↗](https://github.com/ffworker/bytegeist-docs/tree/main/v2)

**Zensical · Markdown · Git snapshots · Documentation as code · Selective private access**

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### [Digital CV ↗](https://github.com/ffworker/my-digital-cv)

The source for my bilingual CV and self-assessed skills pages. CI checks the source; publication to the current Talos Kubernetes deployment requires a separate, explicit revision update. The former Argo CD path is historical.

**HTML/CSS · GitHub Actions · Talos · git-sync**

</td>
</tr>
</table>

### How I work

- **Understand before automating.** I want to know what the system is doing before I hide it behind tooling.
- **Use the right tool, not every tool.** Manual work is fine when automation would add more complexity than value.
- **Know the boundary.** I am comfortable saying when I need documentation, a sandbox, or a second look.
- **Keep recovery boring.** Backups, known-good state, rollback paths and useful documentation matter more than cleverness.

### Evidence, not badges

A few narrow examples with inspectable implementation and explicit success criteria — not generic technology badges:

- **Kubernetes troubleshooting:** [broken Service/EndpointSlice scenario](https://github.com/ffworker/cka-lab/blob/main/scenarios/service-endpoints/scenario.json) + [validator](https://github.com/ffworker/cka-lab/blob/main/scenarios/service-endpoints/validate.sh) requiring the expected selector and two ready backends.
- **Real-world tooling:** [Signaturee v2.0.1](https://github.com/ffworker/signaturee-win/releases/tag/v2.0.1) is a published Windows build; workplace use of the Windows edition is reported by its maintainer, not independent validation of every installation.
- **Reviewable delivery:** [CV validation workflow](https://github.com/ffworker/my-digital-cv/blob/main/.github/workflows/validate.yml) checks generated EN/DE content and the [static regression tests](https://github.com/ffworker/my-digital-cv/blob/main/tests/test_site.py).

These are links to source, validation logic and documented test boundaries. They do **not** claim an independently reproduced live run, continuously healthy private deployment, or completed restore test. See the [skills page](https://cv.bytegeist.dev/skills.html) for self-assessed proficiency and limitations.

---

<sub>More detail without the usual CV skill inflation: <a href="https://cv.bytegeist.dev/skills.html">self-assessed skills →</a></sub>
