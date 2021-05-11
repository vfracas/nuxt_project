<template>
  <div class="container">
    <p class="page_heading">
      Wanna contact us ?
    </p>
    <form action="">

      <label for="fname">First Name</label>
      <input type="text" id="fname" name="firstname" placeholder="First name" required>

      <label for="lname">Last Name</label>
      <input type="text" id="lname" name="lastname" placeholder="Last name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" placeholder="Email" required>

      <label for="subject">Subject</label>
      <textarea id="subject" name="subject" placeholder="Write your message here..." required></textarea>

      <input class="button" type="submit" value="Submit">
    </form>
  </div>
</template>
