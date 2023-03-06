<header>
  <nav>
    <ul>
      <li>
        <a href="/"> Home </a>
      </li>
      <li>
        <a href="/projects"> Projects </a>
      </li>
      <li>
        <a href="/about"> About </a>
      </li>
      <li>
        <a href="/contact"> Contact </a>
      </li>
      <li>
        <a href="/uses"> Uses </a>
      </li>
    </ul>
  </nav>
</header>

<style>
  header {
    display: flex;
    flex-wrap: wrap;
    justify-content: right;
    padding: 1rem;
    margin-right: 4rem;
  }

  ul {
    display: flex;
    gap: 3rem;
    list-style-type: none;
    margin: 0;
  }

  a {
    color: inherit;
    text-decoration: none;
  }

  @media only screen and (max-width: 600px) {
    header {
      margin: auto;
      justify-content: center;
    }

    ul {
      gap: 1rem;
      padding: 0;
    }
  }
</style>
