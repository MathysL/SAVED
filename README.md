SAVED, an interest(ing) crypto currency 
========================================

==== > Tweet #SAVED 2 get $SAVED >====
=======================================


What is SAVED?
----------------
SAVED is a crypto-currency that gains in value and is never ment to be less than its current value (in volume points).

SAVED is a fork of Bitcoin (an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Bitcoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network).

SAVED is the name of open source software which enables the use of this currency.
As an addition to to orginal code,the price of 1 SAVED coin will increase 1% per month and/or later on with one cent SAVED or an increase of 0.01BTC (on top of its previous monthly price in SAVED/BTC).
Started from 1-1-2019 at a price of 1 BTC per 1 SAVED.
(Currently at 1.08 BTC/SAVED)

Base of the code for SAVED currency is deployed on 2 networks that interact (testfase)
One is the Bitcoin LN network 
( view on X-Chain(ge) Crypto-bridge LN network: /market/SAVED_BTC
and the other is the Orginal Bitcoin Code* before the Fork (19-08-2019).

Ps.For the SAVED wallet visit the X-Chain link to create one.

*The orginal Code before the Fork.
For more information, as well as an immediately useable, binary version of
the Bitcoin Core software, see https://bitcoincore.org/en/download/, or read the
[original whitepaper](https://bitcoincore.org/bitcoin.pdf).

License
-------

Bitcoin Core* is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.
SAVED will follow up a with a seperate addition to this license to only use the Open Source code for Bitcoin as MIT Open Source (and not the SAVED implementations and/or additions that may be involved ,like 3rd party licence or links to API's or support).


Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/MathysL/SAVED/tags) wil be created to indicate new official, stable release versions of SAVED/Bitcoin Code.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md)
and useful hints for developers can be found in [doc/developer-notes.md](doc/developer-notes.md).

Testing*
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing*

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations*
------------

Changes to translations as well as new translations can be submitted to
[Bitcoin Core's Transifex page](https://www.transifex.com/bitcoin/bitcoin/).

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.

Translators should also subscribe to the [mailing list](https://groups.google.com/forum/#!forum/bitcoin-translators).
