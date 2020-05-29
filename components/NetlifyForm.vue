<template>
  <form
    netlify-honeypot="seek-field"
    name="workshop-interest"
    method="POST"
    data-netlify="true"
    class="mb-5"
  >
    <label class="hidden"
      >Don't fill out if you're a human: <input name="seek-field-2" type="text"
    /></label>
    <label class="form-label" for="workshop-interest-email">
      Email Address
      <input
        id="workshop-interest-email"
        class="form-input"
        type="email"
        name="workshop-interest-email"
      />
    </label>
    <button class="form-submit" type="submit">Sign up</button>
  </form>
</template>
