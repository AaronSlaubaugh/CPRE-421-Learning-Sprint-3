Timing Side-Channel Lab
An interactive, browser-based teaching module about timing side channels and algorithmic complexity.
Run it
Download or clone this repository.
Open `index.html` in any modern web browser.
Enter a secret string and a guess, choose a comparison strategy, and select Run comparison.
No build tools, server, dependencies, or internet connection are required.
What it teaches
Early-exit comparison: stops at the first mismatch, so the number of character checks depends on the matching prefix.
Constant-work comparison model: examines every position up to the maximum input length, avoiding mismatch-position-dependent work in this simplified model.
Complexity: both approaches are linear in input length in the worst case, but Big-O alone does not describe data-dependent timing.
Measurement noise: a slider adds simulated timing variation to demonstrate why side-channel measurements often require repeated observations.
Safety and scope
This is a local educational simulation. It does not perform network requests, attack a real service, or use real credentials. The displayed timing values are illustrative units, not measured CPU timings. Real constant-time implementations require careful treatment of compiler optimizations, memory access, and hardware behavior.
Files
`index.html` — complete standalone interactive app.
