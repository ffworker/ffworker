<div align="center">

# Dennis Kappel

**System Administrator · Linux · Infrastructure · Networking**

I like knowing why a system works — and why it stopped working.

[CV](https://cv.bytegeist.dev) · [Self-assessed skills](https://cv.bytegeist.dev/skills.html) · [Repositories](https://github.com/ffworker?tab=repositories)

</div>

---

### What I work with

`Linux` · `Bash` · `Docker / Compose` · `Proxmox` · `Networking` · `NetBird / VPN` · `Kubernetes / k3s` · `GitHub Actions` · `NFS / SMB` · `Prometheus / Grafana`

I work best when I can understand the whole path: host → network → service → user. I use documentation, search and AI where they make me faster, but I don't treat generated output as understanding. If I can't reason about a change yet, it belongs in a lab first.

### Selected work

<table>
<tr>
<td colspan="2" valign="top">

#### [CKA Lab ↗](https://github.com/ffworker/cka-lab)

A Kubernetes learning experiment: eight break/fix missions, real-state validators, and an optional AI tutor designed to give hints rather than solve the task. The learning loop is being re-evaluated before claiming practical outcomes.

**Kubernetes · Troubleshooting · Learning by doing**

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### [Signaturee ↗](https://signaturee.bytegeist.dev/)

**Windows — available:** a self-hosted browser workflow for IT-managed and employee self-service signatures, using existing templates and Active Directory. Employee lookup, preflight, preview and targeted runs of up to 50 users reduce repeated manual setup. LibreOffice provides RTF conversion; generated Classic Outlook files are not native new Outlook/web deployment.

**Linux — experimental:** an independently developed Docker-first edition with offline generation, CLI workflows and a limited development UI. Real LDAP acceptance and the full authenticated UI remain pending.

[Explore Signaturee ↗](https://signaturee.bytegeist.dev/)

**PowerShell · Node.js · Active Directory · LibreOffice · IT workflows**

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
- **Reviewable delivery:** [CV validation workflow](https://github.com/ffworker/my-digital-cv/blob/main/.github/workflows/validate.yml) checks generated EN/DE content and the [static regression tests](https://github.com/ffworker/my-digital-cv/blob/main/tests/test_site.py).

These are links to source, validation logic and documented test boundaries. They do **not** claim an independently reproduced live run, continuously healthy private deployment, or completed restore test. See the [skills page](https://cv.bytegeist.dev/skills.html) for self-assessed proficiency and limitations.

---

<sub>More detail without the usual CV skill inflation: <a href="https://cv.bytegeist.dev/skills.html">self-assessed skills →</a></sub>
