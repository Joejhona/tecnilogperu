<template>
  <section id="iq-feature" class="pb-0">
    <div class="container">
      <div class="row justify-content-center position-relative">
        <div class="col-lg-8">
          <VTwoSectionTitle :title-section-prop="titleSectionProp" />
        </div>
        <div v-for="(list,index) in lists" :key="index" class="col-lg-6">
          <div :class="'color-palette wow fadeInUp   text-left'+' '+list.hoverclass">
            <div class="media">
              <div class="circle-icon">
                <i :class="list.icon" aria-hidden="true" />
              </div>
              <div class="media-body">
                <h5 class="color-text mb-2">
                  {{ list.title }}
                </h5>
                <p class="mb-0">
                  {{ list.subtitle }}
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="iq-objects  style-two left-top">
          <span class="iq-objects-02">
            <img src="../../assets/sofbox-v2/images/home-7/704.png" alt="drive02">
          </span>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'Howitworks',
  data () {
    return {
      titleSectionProp: {
        title: 'How Does Sofbox Work?',
        description: 'If you are planning on developing a product landing app or website,take a look at this beautiful-crafted'
      },
      lists: [
        {

          hoverclass: 'purple-hover',
          icon: 'flaticon flaticon-accounting',
          title: 'Customized Invoices',
          subtitle: 'There are many variations of passages of Lorem Ipsum available.'
        },
        {

          hoverclass: 'org-hover',
          icon: 'flaticon flaticon-professional',
          title: 'Stock Management',
          subtitle: 'There are many variations of passages of Lorem Ipsum available.'
        },
        {

          hoverclass: 'green-hover',
          icon: 'flaticon flaticon-document-1',
          title: 'Receivable & Payables',
          subtitle: 'There are many variations of passages of Lorem Ipsum available.'
        },
        {

          hoverclass: 'purple-hover',
          icon: 'flaticon flaticon-growth-1',
          title: ' Manage Bills & Expenses',
          subtitle: 'There are many variations of passages of Lorem Ipsum available.'
        }
      ]
    }
  }
}
</script>
