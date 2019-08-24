<template>
<div class="container">
    <router-link to="/"><img src="~/assets/iTerm2-v3-Hero-logo-icon.jpg" alt="home" class="term"></router-link>
    <div class="container">

	<div class="row">
      <div class="col-md-12 col-md-offset-3">
        <div class="well well-sm">
          <form class="form-horizontal" action="" method="post">
          <fieldset>
            <legend class="text-center">Contact me</legend>
    
            <!-- Name input-->
            <div class="form-group">
              <label class="col-md-6 control-label" for="name">Name</label>
              <div class="col-md-9">
                <input id="name" name="name" type="text" placeholder="Your name" class="form-control">
              </div>
            </div>
    
            <!-- Email input-->
            <div class="form-group">
              <label class="col-md-6 control-label" for="email">Your E-mail</label>
              <div class="col-md-9">
                <input id="email" name="email" type="text" placeholder="Your email" class="form-control">
              </div>
            </div>
    
            <!-- Message body -->
            <div class="form-group">
              <label class="col-md-6 control-label" for="message">Your message</label>
              <div class="col-md-12">
                <textarea class="form-control" id="message" name="message" placeholder="Please enter your message here..." rows="5"></textarea>
              </div>
            </div>
    
            <!-- Form actions -->
            <div class="form-group">
              <!-- <div class="col-md-6 text-right"> -->
                  <div class="text-center">
                <button type="submit" class="btn btn-primary btn-lg">Submit</button>
              </div>
            </div>
          </fieldset>
          </form>
        </div>
      </div>
	</div>
</div>
</div>
</template>

<script>
export default {
    
}
</script>

<style>
/* .container{
  padding: 100px;
} */

body {
    padding-top:20px;
}

.term{
    width: 50px;
    height: 50px;
}
</style>
