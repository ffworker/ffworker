<div align="center">

# Dennis Kappel

**Systems administration · Linux · infrastructure · automation**

I like knowing why a system works — and why it stopped working.

[CV](https://cv.bytegeist.dev) · [Self-assessed skills](https://cv.bytegeist.dev/skills.html) · [Repositories](https://github.com/ffworker?tab=repositories)

</div>

---

### What I work with

`Linux` · `Bash` · `Networking` · `Docker / Compose` · `Kubernetes / Talos` · `PowerShell` · `GitHub Actions` · `NFS / SMB` · `Prometheus / Grafana`

I work best when I can understand the whole path: host → network → service → user. Documentation, search and AI make me faster, but generated output is not understanding by itself. If I cannot reason about a change yet, it belongs in a lab first.

### Selected work

<table>
<tr>
<td width="50%" valign="top">

#### [Signaturee ↗](https://github.com/ffworker/Signaturee-public)

A self-hosted Windows application for generating and deploying Outlook signatures from Active Directory. It combines a web UI, a Node.js API and a PowerShell generator, with template mapping, preflight checks and LDAP self-service.

The current public release is deliberately narrower than a generic signature platform: it uses existing templates and is not a signature designer.

**Windows · Active Directory · Node.js · PowerShell**

</td>
<td width="50%" valign="top">

#### [AccessLens ↗](https://github.com/ffworker/accesslens)

A Rust metadata-only browser for effective file access. It compares identities and shows the evidence behind a result without reading file contents, changing ACLs, impersonating users or silently elevating privileges.

This is a preview build, with real AD/SMB acceptance still treated as an open validation step.

**Rust · Windows · Linux · Authz · SMB**

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Digital CV ↗](https://github.com/ffworker/my-digital-cv)

The portfolio itself: a bilingual static CV with generated skills pages, explicit technical evidence and a separate, reviewable deployment pin to the live site.

The skills page shows where I work independently, where I use documentation or AI, and where I would stay in a lab or ask for review.

**HTML/CSS · Python · GitHub Actions · GitOps**

</td>
<td width="50%" valign="top">

#### [Documentation Systems Blueprint ↗](https://github.com/ffworker/documentation-systems-blueprint)

A vendor-neutral blueprint for evaluating, designing, deploying, migrating and handing over documentation platforms. Docmost is included as a reference implementation, not as a claim about a customer deployment.

The repository focuses on ownership, recovery, migration evidence and operational acceptance rather than just installing a tool.

**Architecture · Documentation · Migration · Operations**

</td>
</tr>
</table>

### A note on scope

I keep this page to work I can currently explain and verify. Older lab repositories and Bytegeist Docs remain on GitHub, but they are not part of this selection.

### How I work

- **Understand before automating.** I want to know what the system is doing before I hide it behind tooling.
- **Use the right tool, not every tool.** Manual work is fine when automation would add more complexity than value.
- **Know the boundary.** I am comfortable saying when I need documentation, a sandbox, or a second look.
- **Keep recovery boring.** Backups, known-good state, rollback paths and useful documentation matter more than cleverness.

### Evidence, not badges

[Signaturee quality gate](https://github.com/ffworker/Signaturee-public/actions/workflows/quality-gate.yml) · [AccessLens validation](https://github.com/ffworker/accesslens/actions/workflows/ci.yml) · [Digital CV validation](https://github.com/ffworker/my-digital-cv/actions/workflows/validate.yml) · [Documentation blueprint validation](https://github.com/ffworker/documentation-systems-blueprint/actions/workflows/validate.yml)

---

<sub>More detail without the usual CV skill inflation: <a href="https://cv.bytegeist.dev/skills.html">self-assessed skills →</a></sub>
