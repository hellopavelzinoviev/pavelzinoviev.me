<template>
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
</template>

<style>
body {
  margin: 0;
  font-family: monospace;
}
section {
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 100vh;
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
