<template>
<section class="pt-0" id="iq-contact">
	<div class="container">
		<div class="row">
			<div class="col-lg-12">
				<div class="title-box">
					<h2>Contact with our team</h2>
					<p>If you are planning on developing a product landing.</p>
				</div>
			</div>
		</div>
		<div class="row">
			<div class="col-lg-6">
				<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6304.829986131271!2d-122.4746968033092!3d37.80374752160443!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808586e6302615a1%3A0x86bd130251757c00!2sStorey+Ave%2C+San+Francisco%2C+CA+94129!5e0!3m2!1sen!2sus!4v1435826432051" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
			</div>
			<div class="col-lg-6">
				<div class="">
					<img class="img-fluid" src="../../assets/sofbox-v2/images/home-1/35.png" alt="img">
					<h5 class="mb-3 mt-5">9840 Shore St. Fond Du Lac, WI 54935</h5>
					<p class="mb-0">0 1223 456 789</p>
					<p class="mb-0">mail@sofbox.com</p>
					<div class="deatils-social mt-5 mb-4"><ul class="share-social  list-inline p-0"><li class="list-inline-item"><a href="#"><i class="fab fa-facebook-f"></i></a></li><li class="list-inline-item"><a href="#"><i class="fab fa-twitter"></i></a></li><li class="list-inline-item"><a href="#"><i class="fab fa-github"></i></a></li><li class="list-inline-item"><a href="#"><i class="fab fa-instagram"></i></a></li></ul></div>
					<h4 class="mb-4">Get in Touch</h4>
					<form>
						<div class="row">
							<div class="col-lg-6">  <input type="text" class="form-control" id="inputName" placeholder="Your Name"> </div>
							<div class="col-lg-6">   <input type="Email" class="form-control" id="inputEmail" placeholder="Your Email"></div>
							<div class="col-lg-12">  <input type="text" class="form-control" id="inputSubject" placeholder="Your Subject"></div>
							<div class="col-lg-12"> <textarea class="form-control" id="exampleFormControlTextarea1" rows="7" placeholder="Your Message"></textarea>
							</div>
							<div class="col-lg-12">
								<a class="button" href="">Send Message</a>
							</div>
						</div>
					</form>
				</div>
			</div>
		</div>
	</div>
</section>
</template>
<script>
import contactLogo from '../../assets/sofbox-v2/images/home-1/35.png'
export default {
  name: 'Contact',
  data () {
    return {
      titleSectionProp2: {
        title: 'Contact with our team',
        description: 'If you are planning on developing a product landing'
      },

      contactSectionProp: {
        class: 'pt-0',
        id: 'iq-contact'
      },
      contactDetail: {
        logo: contactLogo,
        address: '9840 Shore St. Fond Du Lac, WI 54935',
        number: '0 1223 456 789',
        mail: 'mail@sofbox.com'
      }
    }
  }
}
</script>
