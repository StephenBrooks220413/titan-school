<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <br /><br />
    <div class="container">
      <div class="row text-center">
        <div class="col-md-4 hover-shadow">
          <img src="../assets/apple.png" alt="" />
          <h4 class="text-red">
            School Nutrition Professionals 〉
          </h4>
          <p class="content">
            TITAN was founded in response to listening to the specific needs of
            School Nutrition Professionals. Learn more about how TITAN can make
            your program more successful and your life easier.
          </p>
        </div>
        <div class="col-md-4 hover-shadow">
          <img src="../assets/itpro.png" alt="" />
          <h4 class="text-blue">
            District IT Professionals 〉
          </h4>
          <p class="content">
            TITAN’s founders are school IT veterans and we respect that even the
            best industry solutions need to function seamlessly with legacy
            systems. Learn more about our 100% cloud based, secure and scalable,
            web-based management solutions.
          </p>
        </div>
        <div class="col-md-4 hover-shadow">
          <img src="../assets/families.png" alt="" />
          <h4 class="text-orange">
            Families 〉
          </h4>
          <p class="content">
            TITAN understands that happy parents contribute to a successful
            program. Learn more about our 24-hour, web-based, real time, secure
            access to accounts and the ability to manage multiple children’s
            meal plans throughout a school district.
          </p>
        </div>
      </div>
    </div>
    <div class="frame">
      <iframe
        width="100%"
        height="544"
        src="https://www.youtube.com/embed/B2Vqitk-tVM"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
      <br />
      <br />
      <br />
      <hr class="bg-white" />
      <br /><br />
      <div class="container space text-start text-white">
        <h1>Intuitive School Solutions</h1>
        TITAN’s web-based school nutrition solutions make your operations
        stronger, more effective, and efficient. We provide simple
        straight-forward, yet comprehensive management and communications tools
        with a revolutionary, all-inclusive subscription model. Budget-friendly,
        transparent pricing begins here.
      </div>
    </div>
    <br />
    <br />
    <br />
    <hr />
    <br />
    <br />
    <br />
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div class="text-start">
            <h1 class="text-success">Testimonials</h1>
            I was impressed with TITAN School Solutions because their up to date
            technology was able to connect with our student data system which
            helped save me time by not having to enter every student manually.
            After a 5-minute conversation on the phone, they were able to
            transfer all our information and have our new system up and ready to
            run in 48 hours.
            <br /><br />
            The one thing I liked was they were only a phone call away and they
            handled every situation quickly, efficiently, and with a great
            attitude. I found the experience to be pain free and quite
            enjoyable. <br /><br />
            I would recommend TITAN to any school that is looking for an updated
            change that works for the whole Corporation. Jessica Murray, SNS
            Director Nutrition Services—West Central School Coporation, Indiana.
            <br /><br />
            <span class="text-orange">
              <h5>Jessica Murray, SNS</h5>
              Director Nutrition Services—West Central School Coporation,
              Indiana
            </span>
            <br /><br />
            <a href="#" class="btn bg-orange">Testimonial & Case Studies</a>
          </div>
          <br />
          <br />
          <br />
        </div>
        <div class="col-md-6">
          <h2 class="text-success">Clients</h2>
          <br />
          <div class="container">
            <div class="row">
              <img src="../assets/background.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-bg">
      <div class="container">
        <div class="footer-text text-start">
          <h2>
            Upcoming <br />
            Trade Shows
          </h2>
          <button class="btn">View Trade Shows</button>
        </div>
      </div>
    </div>
    <div class="footer-contact">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <div class="footer-text text-start">
              <h2>
                Learn More
              </h2>
              <p>
                The school nutrition industry is dynamic and always changing.
                Please Please join our mailing list to receive timely industry
                news and including chances to meet TITAN representatives at your
                state’s nutrition association conference. We can also let you
                know about informational webinars and open houses in your area.
                Everyone wins with TITAN. Join us!
              </p>
            </div>
          </div>
          <div class="col-md-6">
            <br /><br />
            <form
              name="contact"
              method="POST"
              data-netlify="true"
              honeypot="netlify"
            >
              <!-- Name input -->
              <div class="form-outline mb-4">
                <input type="text" id="form4Example1" class="form-control" />
                <label class="form-label" for="form4Example1"
                  >Name / Job Title</label
                >
              </div>

              <!-- school input -->
              <div class="form-outline mb-4">
                <input type="text" id="form4Example1" class="form-control" />
                <label class="form-label" for="form4Example1"
                  >School District</label
                >
              </div>

              <!-- Email input -->
              <div class="form-outline mb-4">
                <input type="email" id="form4Example2" class="form-control" />
                <label class="form-label" for="form4Example2"
                  >Email address</label
                >
              </div>

              <!-- Message input -->
              <div class="form-outline mb-4">
                <textarea
                  class="form-control"
                  id="form4Example3"
                  rows="4"
                ></textarea>
                <label class="form-label" for="form4Example3">Message</label>
              </div>

              <!-- Checkbox -->
              <div class="form-check d-flex justify-content-center mb-4">
                <input
                  class="form-check-input me-2"
                  type="checkbox"
                  value=""
                  id="form4Example4"
                  checked
                />
                <label class="form-check-label" for="form4Example4">
                  Send me a copy of this message
                </label>
              </div>

              <!-- Submit button -->
              <button type="submit" class="btn btn-primary btn-block mb-4">
                Send
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String
  }
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.text-red {
  color: red;
}
.text-blue {
  color: rgb(76, 76, 214);
}
.text-orange {
  color: rgb(236, 189, 100);
}
.content {
  font-size: 17px;
  margin-top: 15px;
  margin-bottom: 10px;
}
.frame {
  background: url("https://www.titank12.com/application/files/6915/5450/9042/bg_section_teal_green.png")
    no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  margin-bottom: 60px;
  height: auto;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-left: 20px;
  padding-right: 20px;
  margin-top: 60px;
  width: 100%;
  margin-left: auto;
  margin-right: auto;
}
.footer-bg {
  background-color: teal;
  width: 100%;
  height: 50vh;
  color: white;

  button {
    border-radius: 30px;
    background-color: rgb(25, 155, 155);
    color: white;
  }
}
.footer-text {
  padding-top: 100px;
}
.space {
  padding-bottom: 50px;
}
.bg-orange {
  background-color: rgb(25, 155, 155);
  color: white;
  border-radius: 30px;
}
/*footer contact*/
.footer-contact {
  background-color: rgb(233, 177, 72);
  width: 100%;
  height: auto;
  padding-top: 60px;
  padding-bottom: 60px;

  input {
    border-radius: 7px;
    background-color: white;
  }
  textarea {
    border-radius: 7px;
    background-color: white;
  }
}
</style>
