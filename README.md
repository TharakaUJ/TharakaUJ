<style>
     .container {
      position: relative;
      height: 200px;
    }

    .animated-text {
      position: absolute;
      width: 0;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-family: Arial, sans-serif;
      font-size: 24px;
      color: white;
      white-space: nowrap;
      overflow: hidden;
      border-right: 2px solid transparent;
      animation: typing 1s steps(10, end) 7.5s forwards, blink-caret 0.5s step-end 7.5s infinite;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 150px }
    }

    @keyframes blink-caret {
      from, to { border-color: transparent }
      50% { border-color: gray; }
    }
</style>
<div class="container">
<img position=fixed width="200" height="auto" alt="" src="images/helloworld.svg"/>
    <div class="animated-text">
        Hello World!
    </div>
</div>


### Hello World 👋


I'm a programmer who loves math—because debugging code wasn't challenging enough.
<!--
**TUJayasena/TUJayasena** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
