<h1 align="center">Contributing to X Scripts</h1>

<p align="center">
  Thanks for helping improve <b>x</b>, the script repository used to configure and refresh X environments.
</p>

<hr />

<h2 id="how-to-contribute" align="center">How to Contribute</h2>

<ol>
  <li>Fork the repository and create a branch from <code>main</code>.</li>
  <li>Make focused changes (one feature/fix per pull request).</li>
  <li>Test scripts on the target platform (Linux distro and/or WSL).</li>
  <li>Open a pull request with clear context, steps to test, and rollback notes if relevant.</li>
</ol>

<h2 id="repository-focus" align="center">Repository Focus</h2>

<ul>
  <li><code>x.sh</code>: base post-boot setup and environment refresh script.</li>
  <li><code>scripts/</code>: optional modular add-ons.</li>
  <li><code>wsl/</code>: setup and install scripts for WSL environments.</li>
</ul>

<h2 id="contribution-rules" align="center">Contribution Rules</h2>

<ul>
  <li>Keep scripts idempotent when possible (safe to run more than once).</li>
  <li>Prefer explicit checks before system modifications.</li>
  <li>Document new behavior in <code>README.md</code> or module readmes.</li>
  <li>Never commit secrets, tokens, private keys, or machine-specific credentials.</li>
  <li>For vulnerability reports, use <a href="./SECURITY.md">SECURITY.md</a> instead of public issues.</li>
</ul>

<h2 id="behavior" align="center">Community Behavior</h2>

<p>
  By participating, you agree to follow <a href="./CODE_OF_CONDUCT.md">CODE_OF_CONDUCT.md</a>.
</p>

<hr />

<p align="center"><b>We appreciate every improvement to X scripts.</b></p>