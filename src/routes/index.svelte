<script>
  import Stats from "./_index/Stats.svelte";
  import Partners from "./_index/Partners.svelte";
  import Projects from "./_index/Projects.svelte";
  import GhButtons from "./_index/GhButtons.svelte";
</script>

<style>
  .medals {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
  }

  @media screen and (max-width: 900px) {
    .medals img {
      width: 100vw;
      height: auto;
      max-width: none;
      margin-left: -3rem;
      margin-right: -3rem;
      flex-shrink: 0;
      order: 1;
    }
  }
</style>

<svelte:head>
  <title>LeapDAO</title>
</svelte:head>
<div class="content">
  <header>
    <h1>LeapDAO</h1>
    <p class="subtitle">Scaling for decentralized apps</p>
    <p>
      We're an open source community bringing scalability to Ethereum using
      Plasma.
    </p>
  </header>

  <Stats />
  <Partners />

  <section class="section">
    <header>
      <h2>Key advantages</h2>
      <p>
        The Leap&nbsp;Network combines scalability, ease of use and security —
        all in one.
      </p>
    </header>

    <div class="cols">
      <div class="col">
        <h4>Smart and fast</h4>
        <p>
          Allows for smart contracts to be executed on Layer-2.
          <br />
          Up to 4000 transactions per second,
          <br />
          3 seconds block time.
        </p>
      </div>
      <div class="col">
        <h4>Easy on-boarding</h4>
        <p>
          All you need is a wallet - contracts can pay for gas (no ETH balance
          required).
        </p>
      </div>
      <div class="col">
        <h4>Security in mind</h4>
        <p>All funds secured by full PoW of Ethereum mainnet.</p>
        <p>Proof of Stake prevents censorship by a single operator.</p>
      </div>
    </div>

    <footer>
      <a
        href="https://leapdao.org/whitepaper/"
        target="_blank"
        class="button button-primary">
        White paper
      </a>
    </footer>
  </section>

  <Projects />

  <section class="section">
    <header>
      <h2>Build</h2>
    </header>
    <div class="cols">
      <div class="col">
        <h4>Beginners guide</h4>
        <p>
          It is easy and straightforward to start using the Leap&nbsp;Network.
          Learn how to run smart contracts on Plasma with Spending Conditions.
        </p>
        <p>
          <a
            href="https://docs.leapdao.org"
            target="_blank"
            rel="noopener noreferrer">
            Docs
          </a>
        </p>
      </div>
      <div class="col">
        <h4>Your dApp on the Leap&nbsp;Network</h4>
        <p>
          No matter if you want to create a new dApp or already have one: check
          out simple use case examples.
        </p>
        <p>
          <a
            href="https://github.com/leapdao/spending-conditions/tree/master/contracts"
            target="_blank"
            rel="noopener noreferrer">
            Spending conditions examples
          </a>
        </p>
      </div>
      <div class="col">
        <h4>Give feedback, request&nbsp;features</h4>
        <p>
          We work for the developers, so your feedback is very valuable. Request
          new features and suggest improvements.
        </p>
        <p>
          <a
            href="https://github.com/search?q=is%3Aopen+is%3Aissue+archived%3Afalse+user%3Aleapdao"
            target="_blank"
            rel="noopener noreferrer">
            Github issues
          </a>
        </p>
      </div>
    </div>

    <footer>
      <a
        href="https://docs.leapdao.org/recipes/send-transfer/"
        target="_blank"
        class="button button-primary">
        Get started
      </a>
    </footer>
  </section>

  <section class="section">
    <header>
      <h2>Validate</h2>
    </header>
    <div class="cols">
      <div class="col">
        <h4>Become a validator</h4>
        <p>
          Run a node and stay in sync with the network, stake a lot of tokens,
          and earn more.
        </p>
        <p>
          <a
            href="https://docs.google.com/presentation/d/e/2PACX-1vTZj5bBhYUObaWtrtOvoIq6SGJG-oAYh-C1QUFsEwETOWkRRSWI1sDKpvVI-MTbciVAPhiaQPNwx2aI/pub?start=false&loop=false&delayms=3000&slide=id.g6c57165488_0_0" target="_blank">
            Validator Introduction Presentation
          </a>
        </p>
      </div>
      <div class="col">
        <h4>Strenghten the chain</h4>
        <p>
          If there is only one operator, then he can censor transactions. With
          multiple operators the chain becomes more censorship resistant.
        </p>
      </div>
      <div class="col">
        <h4>Improve Ethereum</h4>
        <p>
          Help Ethereum scale on Layer 2 and achieve mass adoption.
          <br />
          Do PoS on Ethereum before Ethereum does PoS.
        </p>
      </div>
    </div>
    <a
        href="/validate"
        target="_blank"
        class="button button-primary"
        style="margin-top: 40px;">
        Apply now
      </a>
  </section>

  <section class="section">
    <header>
      <h2>Contribute</h2>
    </header>
    <div class="cols">
      <div class="col">
        <h4>Contribute code</h4>
        <p>
          All our code is open-source and stored on
          <a
            href="https://github.com/leapdao"
            target="_blank"
            rel="noopener noreferrer">
            GitHub
          </a>
          . Check out repos, report bugs, find solutions, propose features.
        </p>
      </div>
      <div class="col">
        <h4>Contribute support</h4>
        <p>
          Our aim is to help others build their future. And we also need your
          help for that. Join open Leap community!
        </p>
      </div>
      <div class="col">
        <h4>Get rewarded</h4>
        <p>
          We aim to reward any contribution to LeapDAO using bounties, salaries
          and hourly-based compensation.
        </p>
        <p>
          <a
            href="https://leapdao.org/earn/"
            target="_blank"
            rel="noopener noreferrer">
            Available bounties
          </a>
        </p>
      </div>
    </div>

    <footer>
      <a
        href="https://docs.google.com/forms/d/e/1FAIpQLSd8_wDGDAi__HvfYEWNK_bvJzIkxwHHRVL6AFEfJewBd2Vn9A/viewform"
        target="_blank"
        class="button button-primary">
        Join now
      </a>
    </footer>
  </section>

  <h2>Get involved!</h2>
  <p>
    As an open-source software community, Leap thrives from the efforts of its
    members. Whatever your interests and skills are, there is ample opportunity
    to make the life of Dapps better!
  </p>
</div>

<GhButtons />
<br />
<br />
<div class="medals">
  <img
    src="/img/contrubitons.png"
    width="761"
    height="98"
    alt="Contributions chart" />
</div>
