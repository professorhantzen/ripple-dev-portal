# Contribute Code to ripple-lib

Want to contribute code or a bug report to help improve `ripple-lib`, the official client library for [RippleAPI](rippleapi-reference.html)? RippleAPI is a JavaScript API for interacting with the XRP Ledger. Here’s a roadmap to the high-level tasks that’ll have you reviewing code and functionality in no time.


{% set n = cycler(* range(1,99)) %}

<span class="use-case-step-num">{{n.next()}}</span>
<!-- <span class="use-case-step-length">(1 hour)</span> -->
## <a href="https://github.com/ripple/ripple-lib" target="_blank">Access the `ripple-lib` repo <i class="fa fa-external-link" aria-hidden="true"></i></a> <!--#{ fix for md highlighting_ #}-->

`ripple-lib` is an open-source project. You can take a look at `ripple-lib` code simply by accessing the `ripple-lib` GitHub repo. Before contributing or reporting bugs, we recommend that you get to know the code and developer experience by performing the following tasks.


<span class="use-case-step-num">{{n.next()}}</span>
<!-- <span class="use-case-step-length">(1 hour)</span> -->
## [Set up and run a `rippled` server](manage-the-rippled-server.html)

RippleAPI is an API for interacting with the XRP Ledger. The core peer-to-peer server that manages the XRP Ledger is `rippled`. Optionally, you can set up and run a `rippled` server to understand its developer experience and functionality. Anyone can run their own `rippled` server that follows the network and keeps a complete copy of the XRP Ledger.


<span class="use-case-step-num">{{n.next()}}</span>
<!-- <span class="use-case-step-length">(1 hour)</span> -->
## [Get a Test Net XRP Ledger account](xrp-test-net-faucet.html)

Use the XRP Test Net Faucet to get a test account on the XRP Test Network. If you set up a `rippled` server, you can connect it to the XRP Test Net to make test calls and get to know the XRP Ledger.


<span class="use-case-step-num">{{n.next()}}</span>
<!-- <span class="use-case-step-length">(1 hour)</span> -->
## [Set up your `ripple-lib` development environment](get-started-with-rippleapi-for-javascript.html#environment-setup)

`ripple-lib` requires Node.js and a few dependencies. We recommend using <a href="https://nodejs.org/en/" target="_blank">Node.js v10 LTS <i class="fa fa-external-link" aria-hidden="true"></i></a> <!--#{ fix for md highlighting_ #}--> and <a href="https://yarnpkg.com/en/" target="_blank">Yarn <i class="fa fa-external-link" aria-hidden="true"></i></a> <!--#{ fix for md highlighting_ #}--> dependency management. Also, be sure to create your own fork of the `ripple-lib` repository on GitHub so you can contribute pull requests to the official repo.


<span class="use-case-step-num">{{n.next()}}</span>
<!-- <span class="use-case-step-length">(1 hour)</span> -->
## [Run your first `ripple-lib` script](get-started-with-rippleapi-for-javascript.html#first-rippleapi-script)

Examine and run the `get-account-info.js` script. Use it to get a feel for how RippleAPI scripts work and to verify that your RippleAPI interface is working.


<span class="use-case-step-num">{{n.next()}}</span>
<!-- <span class="use-case-step-length">(1 hour)</span> -->
## <a href="https://github.com/ripple/ripple-lib/pulls" target="_blank">Contribute code <i class="fa fa-external-link" aria-hidden="true"></i></a><!--#{ fix for md highlighting_ #}-->

Now that you have a handle on `ripple-lib`, you may have ideas for how to improve it.

Perhaps you’re developing on the XRP Ledger and want to contribute some code that enables `ripple-lib` to provide a feature your application needs.

Need some inspiration? Take a look at our list of <a href="https://github.com/ripple/ripple-lib/issues?utf8=%E2%9C%93&q=label%3A%22help+wanted%22" target="_blank">Help Wanted issues <i class="fa fa-external-link" aria-hidden="true"></i></a> <!--#{ fix for md highlighting_ #}-->.

Access the `ripple-lib` repo and open an issue or pull request.


<span class="use-case-step-num">{{n.next()}}</span>
<!-- <span class="use-case-step-length">(1 hour)</span> -->
## <a href="https://github.com/ripple/ripple-lib/issues" target="_blank">Report bugs <i class="fa fa-external-link" aria-hidden="true"></i></a><!--#{ fix for md highlighting_ #}-->

As you explore `ripple-lib`, you may find code that you don’t think is working as intended. To report a bug, <a href="https://github.com/ripple/ripple-lib/issues" target="_blank">open an issue <i class="fa fa-external-link" aria-hidden="true"></i></a><!--#{ fix for md highlighting_ #}--> in the `ripple-lib` repo.

If the bug you wish to report is security-related, we urge you to disclose it responsibly through Ripple's <a href="https://ripple.com/bug-bounty/" target="_blank">Bug Bounty program <i class="fa fa-external-link" aria-hidden="true"></i></a>.
