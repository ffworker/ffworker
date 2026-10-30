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
<td width="50%" valign="top">

#### [CKA Lab ↗](https://github.com/ffworker/cka-lab)

A self-hosted Kubernetes study lab: disposable infrastructure, eight break/fix missions, and validators that check live cluster state. The lab is meant for hands-on practice, not as a hosted training service.

**Kubernetes · Terraform · Ansible · Troubleshooting**

</td>
<td width="50%" valign="top">

#### [Proxmox Lab ↗](https://github.com/ffworker/proxmox-lab)

The infrastructure companion to CKA Lab. Terraform/OpenTofu owns bounded VM lifecycles; Ansible configures the guests; teardown checks guard against removing unrelated resources.

**Proxmox · OpenTofu · Ansible · Cloud-Init**

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Signaturee ↗](https://signaturee.bytegeist.dev/)

**Windows — available:** a self-hosted browser workflow for IT-managed and employee self-service signatures, using existing templates and Active Directory. Employee lookup, preflight, preview and targeted runs of up to 50 users reduce repeated manual setup. LibreOffice provides RTF conversion; generated Classic Outlook files are not native new Outlook/web deployment.

**Linux — experimental:** an independently developed Docker-first edition with offline generation, CLI workflows and a limited development UI. Real LDAP acceptance and the full authenticated UI remain pending.

[Website](https://signaturee.bytegeist.dev/) · [Windows source](https://github.com/ffworker/Signaturee-public) · [Releases](https://github.com/ffworker/Signaturee-public/releases) · [Linux development](https://github.com/ffworker/signaturee-linux)

**PowerShell · Node.js · Active Directory · LibreOffice · IT workflows**

</td>
<td width="50%" valign="top">

#### [Bytegeist Docs ↗](https://github.com/ffworker/bytegeist-docs)

A docs-as-code design for aggregating selected documentation from its owning repositories while keeping private operational content out of the public repository. The public code shows the validation and delivery workflows; the rendered site is private.

**Documentation · GitHub Actions · Access boundaries**

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

[CKA lab checks](https://github.com/ffworker/cka-lab/blob/main/.github/workflows/learning-validate.yml) · [Proxmox/IaC checks](https://github.com/ffworker/proxmox-lab/blob/main/.github/workflows/rocky-kubernetes-proxmox-validate.yml) · [Signaturee source and tests](https://github.com/ffworker/Signaturee-public/tree/main/tests) · [Docs CI](https://github.com/ffworker/bytegeist-docs/blob/main/.github/workflows/ci.yml)

These links show source and automated checks, not proof that a particular private deployment is currently healthy.

---

<sub>More detail without the usual CV skill inflation: <a href="https://cv.bytegeist.dev/skills.html">self-assessed skills →</a></sub>
