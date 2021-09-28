<template>
  <div class="container text-white bg-dark">
    <h1>Get In Touch</h1>
    <p>For booking or any other information,feel free to get in touch</p>
    <form>
      <div class="mb-3">
        <label for="exampleInputEmail1" class="form-label"
          >Your name(required)</label
        >
        <input
          id="exampleInputEmail1"
          type="text"
          class="form-control"
          required
          aria-describedby="emailHelp"
        />
      </div>
      <div class="mb-3">
        <label for="exampleInputPassword1" class="form-label"
          >Your Email(required)</label
        >
        <input
          id="exampleInputPassword1"
          type="email"
          class="form-control"
          required
        />
      </div>

      <div class="mb-3">
        <label for="exampleInputPassword1" class="form-label">Subject</label>
        <input
          id="exampleInputPassword1"
          type="text"
          class="form-control"
          required
        />
      </div>

      <div class="mb-3">
          <label for="floatingTextarea2">Your message</label>
        <textarea
        id="floatingTextarea2"
          class="form-control"
          placeholder="Leave a comment here"
          required
          style="height: 100px"
        ></textarea>
        
      </div>

      <button type="submit" class="btn btn-success">Send</button>
    </form>
  </div>
</template>

<script>
export default {}
</script>

<style>
p{
    text-align: center;
}
</style>
