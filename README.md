<style>
.gh{background:var(--surface-2);border:0.5px solid var(--border);border-radius:12px;padding:1.5rem 2rem;font-size:15px;line-height:1.6;color:var(--text-primary)}
.gh h3{font-size:18px;font-weight:500;margin:0 0 .5rem}
.gh p{margin:.6rem 0}
.gh a{color:var(--text-accent);text-decoration:none}
.gh ul{margin:.25rem 0 .8rem;padding-left:1.4rem}
.gh pre{background:var(--surface-1);border-radius:6px;padding:14px 16px;font-family:var(--font-mono);font-size:12.5px;line-height:1.5;overflow-x:auto;margin:1rem 0;white-space:pre}
.gh .lbl{font-weight:500;display:block;margin-top:1.1rem}
</style>
<div class="gh">
<div style="font-size:12px;color:var(--text-muted);margin-bottom:.75rem;font-family:var(--font-mono)">sohaibmohd18 / README.md</div>
<h3>Hi, I'm Sohaib.</h3>
<p>I work on the layer nobody notices until it breaks: the clusters, pipelines, and plumbing that teams build on top of.</p>
<pre><span style="color:var(--text-secondary)">$</span> kubectl describe engineer sohaib

Name:          sohaib
Namespace:     san-jose
Role:          cloud-infrastructure / devops
Uptime:        4y+
Previously:    adobe, axis-bank
Workload:      on-prem gpu kubernetes for llm training + inference
Tooling:       terraform, argocd, helm, istio, prometheus, go, python

Events:
  Type    Reason      Message
  ----    ------      -------
  Normal  Graduated   Master of Science, CSU East Bay</pre>
<span class="lbl">Right now</span>
<p style="margin-top:0">Standing up on-prem Kubernetes so an LLM can train on, and answer questions about. The GPUs are the easy part. Scheduling, storage, and keeping sensitive data on-prem are where it gets interesting.</p>
<span class="lbl">What I believe about infrastructure</span>
<ul><li>The best deploy is a boring one.</li><li>If it isn't in Git, it didn't happen.</li><li>Alert on symptoms, not causes. Dashboards are for humans, pages are for problems.</li><li>Every manual step is a future incident.</li></ul>
<span class="lbl">Building on the side</span>
<p style="margin-top:0"><a href="#">HelmSight</a>: one screen that answers <i>"which of my Helm releases is quietly rotting?"</i> Pod health, chart staleness, values drift, and release status, ranked by severity. Go and React. In progress.</p>
<span class="lbl">Elsewhere</span>
<p style="margin-top:0"><a href="https://linkedin.com/in/sohaib-mohd">LinkedIn</a> · <a href="sohaibmohd313@gmail.com">Email</a></p>
<p style="font-size:12px;color:var(--text-secondary);margin-top:1.2rem">Still automating my automation scripts.</p>
</div>
