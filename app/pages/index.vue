<template>
  <main>
    <header>
      <span>✷✷✷</span>
    </header>
    <section>
      <h1>
        <a href="https://bsky.app/profile/pavelzinoviev.me" target="_blank">pavel zinoviev</a>
      </h1>
      <div>
        <h2>to do:</h2>
        <ul>
          <li aria-checked="true"><span aria-hidden="true">-[x]</span> buy a domain</li>
          <li aria-checked="false"><span aria-hidden="true">-[ ]</span> design the site</li>
          <li aria-checked="false"><span aria-hidden="true">-[ ]</span> build the site</li>
        </ul>
      </div>
    </section>
    <footer>
      <span>2025</span>
      <span>✷✷✷</span>
    </footer>
  </main>
</template>

<style>
body {
  margin: 0;
  font-family: monospace;
}
main {
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 100vh;
}
section {
  flex-grow: 1;
}
footer,
header {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 1em;
  padding: 2em;
}
h1 {
  margin-top: 20vw;
  font-size: 1.5rem;
  font-weight: normal;
}
h2 {
  font-size: 1rem;
  font-weight: normal;
}
a {
  color: inherit;
}
a:hover {
  opacity: 0.5;
}
a[target="_blank"]:after {
  content: "↗";
  margin-left: 0.5rem;
}
ul {
  list-style: none;
  padding: 0;
}
li {
  font-size: 1rem;
}
li[aria-checked="true"] {
  opacity: 0.5;
}
</style>
