<script setup lang="ts">
import { Typed } from "@duskmoon/vue3-typed-js";
import type { TypedOptions } from "@duskmoon/vue3-typed-js";

const options: TypedOptions = {
  strings: [
    "learning cryptography, web, and pwn",
    "p.sendline(b\'A\'*0x1000)",
    "nvim4life",
    "b *main+69",
    "ctf trainings", 
    "cat ./flag.txt",
    "x/50gx 0xfff8881012006147",
    "python solve.py",
    "p.interactive()",
    "\' or 1=1 -- ",
    "b\'\\xd0\\x9d\\xdb\\xf7\\x7f\\x7f\\x00\\x00\'",
    "1337",
    "itecc nst klubb"
  ],
  startDelay: 500,
  backDelay: 1500,
  typeSpeed: 100,
  backSpeed: 60,
  loop: true,
  smartBackspace: true,
}
</script>

<template>
  <Typed :options="options">
    <p class="typed">
      <i class="typing"></i>
    </p>
  </Typed>
</template>
