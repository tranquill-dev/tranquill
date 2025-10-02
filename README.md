<div align="center">
    <img src="https://tranquill-dev.github.io/tranquill/assets/images/outlined_128x.png" alt="tranquill logo" width="48px" height="48px"/>
    <h1>tranquill</h1>
    <h3>Human-like typing automation for Google Chrome.</h3>
</div>

<h2>Overview</h2>
<p>
    <strong>tranquill</strong> is a real-time automated typing bot designed to work seamlessly with Google Chrome. This extension allows you to automate typing tasks on websites such as Google Docs, simulating human-like typing while doing so.

    Using tranquill, you can create realistic edit history
    on your documents, rather than pasting
    and having everything appear at once.

</p>

<h3>⚠️ This code is provided for demonstrational purposes only. I am not liable for any misuse of this extension. Use at your own discretion.</h3>

<h2>Features</h2>
<ul>
	<li><strong>Ghost Mode:</strong> Allows you to type random keys on your keyboard and automatically replaces them with the correct letter from your pasted text.</li>
	<li><strong>Completely Undetectable:</strong> Simulates keypresses in a way that appears to like native keypresses, undetectable to any website.</li>
    <li><strong>Human-like Typing Simulation:</strong> Simulates realistic typing behavior, including variable typing speed, pauses, and delays based on key distances and human typing habits.</li>
    <li><strong>Version Control:</strong> Automatically checks for updates to ensure you always have the latest features and improvements.</li>
    <li><strong>User-Friendly Interface:</strong> Simple and intuitive UI to control and customize your typing tasks.</li>
</ul>

<h2>Installation</h2>
<p>
    <strong>tranquill</strong> takes 30 seconds to install. Watch the video below to proceed:
</p>

<a href="https://drive.google.com/file/d/14vgdbv0LBdTuJebUgVLQIpgE3uccJUvN/view?usp=sharing">Watch Video (0:32)</a>

<h2>Usage</h2>
<p>
    <strong>tranquill</strong> is designed to be intuitive and easy to use. Here's a step-by-step guide on how to use it:
</p>

<h3>Step 1: Open the Extension Popup</h3>
<p>
    Click on the <strong>tranquill</strong> icon in the Chrome toolbar to open the extension's popup interface.
</p>

<img src="https://tranquill-dev.github.io/tranquill/assets/images/gui.png" alt="tranquill gui"/>

<h3>Step 2: Enter Text</h3>
<p>
    In the popup, you will see a text input field labeled "Text Queue". Enter or paste the text that you want <strong>tranquill</strong> to type. Then, press the blue <strong>Save</strong> button.
</p>

<h3>Step 3: Configure Settings</h3>
<p>
    Click the gray <strong>Settings</strong> button. It will open a page for you to configure your typing settings, like the speed, Ghost Mode, and the abort keybind.
</p>

<h3>Step 4: Start Typing</h3>
<p>
    Exit settings if you haven't already and click the big <strong>Start</strong> button. <strong>tranquill</strong> will begin typing the text into the active element on the webpage. The typing speed and behavior will mimic human typing, including natural delays between keystrokes.
</p>

<h3>Step 5: Resetting the Input</h3>
<p>
    If you want to clear the text queue, click the red <strong>Trash</strong> button. This will clear the input field and stop any ongoing typing tasks.
</p>

<h2>Update Notifications</h2>
<p>
    <strong>tranquill</strong> includes a built-in update notification system that checks for new versions each time the extension is reloaded. If a new version is detected, you will receive an update notification directly in your extension. Simply follow the installation guide to update.
</p>

<h3>How to Update</h3>
<ol>
    <li>When an update is available, the extension will automatically show an <strong>Update Required</strong> page.</li>
    <li>Click the <strong>Update Now</strong> button to visit this repository, and follow the installation instructions found above.</li>
</ol>

<h2>Troubleshooting</h2>
<ul>
    <li><strong>Extension Not Loading:</strong> Make sure Developer Mode is enabled and the folder you selected is correct.</li>
    <li><strong>Version Check Failing:</strong> Ensure you have an active internet connection and that github.com is accessible on your WiFi network.</li>
    <li><strong>Typing Issues:</strong> Verify that the active element on the webpage is an input field or editable area where typing is possible.</li>
</ul>
<p>
    For more detailed troubleshooting, please visit the <a href="https://github.com/tranquill-dev/tranquill/issues">issues section</a> of this repository.
</p>

<h2>Obscura configuration</h2>
<p>
    The build pipeline now exposes a configurable JavaScript obfuscation stage called <strong>Obscura</strong>. Its behaviour is driven by the <code>obscura.config.json</code> file in the project root. Adjusting this file lets you fine-tune how aggressively code is transformed while reducing the risk of runtime breakage.
</p>
<ul>
    <li><strong>runtime.mode</strong>: Choose between <code>auto</code>, <code>import</code>, or <code>inline</code> runtime injection. Obscura automatically falls back to a safe option if an incompatible mode is selected.</li>
    <li><strong>virtualization</strong>: Toggle string, template, regular-expression, and numeric literal encryption independently, set minimum numeric thresholds, and exclude fragile literals with <code>skipPatterns</code>.</li>
    <li><strong>rename</strong>: Enable collision-aware renaming with a custom prefix and a list of reserved identifiers.</li>
    <li><strong>plugins</strong>: Enable or disable the scrubber, control-flow normaliser, and grammar camouflage passes, and customise their probabilities.</li>
    <li><strong>diagnostics</strong>: Control console verbosity, request an on-disk diagnostics report (<code>tranquill.obscura-report.json</code>), and include high level summaries of the actions taken for each file.</li>
</ul>
<p>
    During a build Obscura records potential problem spots, such as duplicated runtime injections or identifiers that could shadow runtime helpers, and surfaces them as warnings in both the console and the generated diagnostics report.
</p>

<br>
<div align="center">
    <p>Happy Typing with tranquill!</p>
    <img src="https://tranquill-dev.github.io/tranquill/assets/images/outlined_128x.png" alt="tranquill logo" width="64"/>
</div>
