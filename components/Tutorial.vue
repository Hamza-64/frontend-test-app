<!-- Please remove this file from your project -->
<template>
  <div
    class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0"
  >
  <dialog id="myDialog" class="dialog-cont">
    <div class="dialog">
      {{ message }}
      <button class="dialog-btn" type="button" @click="closeDialog">Close</button>
    </div>
  </dialog>
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8">
      <a
        class="flex justify-center pt-8 sm:pt-0"
        href="https://nuxtjs.org"
        target="_blank"
      >
        <svg
          width="218"
          height="45"
          viewBox="0 0 159 30"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M55.5017 6.81866H60.1727L70.0719 22.9912V6.81866H74.3837V29.7345H69.7446L59.8135 13.5955V29.7345H55.5017V6.81866Z"
            fill="#003543"
          />
          <path
            d="M93.657 29.7344H89.6389V27.1747C88.7241 28.9761 86.8628 29.9904 84.5113 29.9904C80.7869 29.9904 78.3684 27.3059 78.3684 23.4423V13.2339H82.3865V22.5976C82.3865 24.8566 83.7594 26.4276 85.8171 26.4276C88.0712 26.4276 89.6389 24.6598 89.6389 22.2377V13.2339H93.657V29.7344Z"
            fill="#003543"
          />
          <path
            d="M107.64 29.7344L103.784 24.2342L99.9291 29.7344H95.6492L101.596 21.1242L96.1074 13.2339H100.485L103.784 17.9821L107.051 13.2339H111.461L105.94 21.1242L111.886 29.7344H107.64Z"
            fill="#003543"
          />
          <path
            d="M120.053 8.25848V13.2339H124.627V16.6063H120.053V24.7974C120.053 25.0725 120.162 25.3363 120.356 25.531C120.55 25.7257 120.813 25.8353 121.087 25.8357H124.627V29.728H121.98C118.386 29.728 116.035 27.6323 116.035 23.9687V16.6095H112.801V13.2339H114.83C115.776 13.2339 116.327 12.6692 116.327 11.7349V8.25848H120.053Z"
            fill="#003543"
          />
          <path
            d="M134.756 24.5446V6.81866H139.066V23.1864C139.066 27.6067 136.943 29.7345 133.349 29.7345H128.332V25.8421H133.461C133.804 25.8421 134.134 25.7054 134.377 25.4621C134.619 25.2188 134.756 24.8888 134.756 24.5446Z"
            fill="#003543"
          />
          <path
            d="M141.649 22.0409H145.799C146.029 24.6006 147.728 26.2308 150.472 26.2308C152.923 26.2308 154.623 25.2501 154.623 23.2199C154.623 18.3085 142.331 21.7129 142.331 12.9395C142.334 9.17515 145.568 6.55945 150.215 6.55945C155.05 6.55945 158.317 9.34153 158.516 13.6306H154.388C154.193 11.6341 152.632 10.2918 150.207 10.2918C147.953 10.2918 146.548 11.3397 146.548 12.9427C146.548 18.0173 159 14.2226 159 23.1576C159 27.4131 155.504 30 150.474 30C145.279 30 141.882 26.8563 141.654 22.0441"
            fill="#003543"
          />
          <path
            d="M24.7203 29.704H41.1008C41.6211 29.7041 42.1322 29.5669 42.5828 29.3061C43.0334 29.0454 43.4075 28.6704 43.6675 28.2188C43.9275 27.7672 44.0643 27.2549 44.0641 26.7335C44.0639 26.2121 43.9266 25.6999 43.6662 25.2485L32.6655 6.15312C32.4055 5.70162 32.0315 5.32667 31.581 5.06598C31.1305 4.8053 30.6195 4.66805 30.0994 4.66805C29.5792 4.66805 29.0682 4.8053 28.6177 5.06598C28.1672 5.32667 27.7932 5.70162 27.5332 6.15312L24.7203 11.039L19.2208 1.48485C18.9606 1.03338 18.5864 0.658493 18.1358 0.397853C17.6852 0.137213 17.1741 0 16.6538 0C16.1336 0 15.6225 0.137213 15.1719 0.397853C14.7213 0.658493 14.3471 1.03338 14.0868 1.48485L0.397874 25.2485C0.137452 25.6999 0.000226653 26.2121 2.8053e-07 26.7335C-0.000226092 27.2549 0.136554 27.7672 0.396584 28.2188C0.656614 28.6704 1.03072 29.0454 1.48129 29.3061C1.93185 29.5669 2.44298 29.7041 2.96326 29.704H13.2456C17.3195 29.704 20.3239 27.9106 22.3912 24.4118L27.4102 15.7008L30.0986 11.039L38.1667 25.0422H27.4102L24.7203 29.704ZM13.0779 25.0374L5.9022 25.0358L16.6586 6.36589L22.0257 15.7008L18.4322 21.9401C17.0593 24.2103 15.4996 25.0374 13.0779 25.0374Z"
            fill="#00DC82"
          />
        </svg>
      </a>
      <div class="mt-8 bg-white overflow-hidden shadow sm:rounded-lg p-6">
        <h2 class="text-2xl leading-7 font-semibold mb-6">
          Welcome to Tutorial creator Nuxt Application
        </h2>
        <div class="main-form">
          <div class="form-field">
            <label for="name" class="title"><b>Title:</b></label>
            <input type="text" id="name" class="input-field" v-model="title">
          </div>
          <div class="form-field">
            <label for="name" class="desc"><b>Description:</b></label>
            <textarea  type="text" id="name" class="input-field" v-model="description"></textarea>
          </div>
          <div class="form-btn-cont">
            <button class="form-btn" type="button" @click="submitData">Save</button>
          </div>
          <div class="main-data-cont">
            <div class="data-cont mb-3" v-for="item in tutorialsArr" :key="item._id">
              <div>
                <label for="name"><b>Title:</b></label> <span>{{item.title}}</span>
              </div>
              <div>
                <label for="name"><b>Description:</b></label> <span class="desc-cont">{{item.description}}</span>
              </div>
              <div class="del-btn-cont">
                <button class="del-btn" type="button" @click="delData(item._id)">Delete</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NuxtTutorial',

  data() {
    return {
      title: "",
      description:"",
      tutorialsArr: [],
      dialog: "",
      message:""
    }
  },

  mounted () {
    this.dialog = document.getElementById("myDialog");
    this.getData()
  },

  methods: {
   async submitData() {
    if(!this.title || !this.description){
      this.dialog.show();
      this.message= "Please enter correct data.."
    }
    else {
      const payload= {
        title: this.title,
        description: this.description
      }
      const res = await this.$axios.$post('/api/tutorials/create',payload)
        this.title = ""
        this.description = ""
        this.message = "Data is saved...."
        this.dialog.show()
        this.getData()
        return res;
      }
    },

    async getData() {
      const res = await this.$axios.$get('/api/tutorials/getTutorials')
      this.tutorialsArr = [...res]
      return res;
    },

    async delData(delId) {
      const res = await this.$axios.$delete('/api/tutorials/deleteTutorial',{ data: { id: delId } })
      if(res._id){
        this.message = "Data deleted succesfully...."
        this.dialog.show()
        this.getData()
      }
      return res;
    },

    closeDialog() {
      this.dialog.close();
    }
  },
}
</script>
<style scoped>
  .input-field{
    background-color: rgb(234, 220, 220);
    width: 100%;
    border-radius: 5px;
    padding: 3px;
  }
  .main-form{
    display: flex;
    flex-direction: column;
  }
  .form-field{
    margin-bottom: 10px;
    display: flex;
  }
  .form-btn{
    background-color: blue;
    width: 130px;
    color: white;
    border-radius: 5px;
    height: 30px;
    margin: 5px;
    margin-top: 10px;
  }
  .del-btn{
    background-color: red;
    width: 70px;
    color: white;
    border-radius: 5px;
    height: 30px;
  }
  .del-btn-cont{
    display: flex;
    flex-direction: row-reverse;
  }
  .dialog-btn{
    background-color: black;
    color: white;
    border-radius: 5px;
    height: 20px;
    width: 50px;
    font-size: small;
    margin: 15px;
    border: none;
  }
  .form-btn-cont{
    display: flex;
    justify-content: center;
    margin-bottom: 10px;
  }
  .main-data-cont{
    height: 350px;
    /* background-color: green; */
    overflow-y: auto;
  }
  .data-cont{
    display: flex;
    flex-direction: column;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
    padding: 5px;
    border-radius: 5px;
  }
  .data-cont:hover {
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  }
  .dialog{
    /* background-color: rgb(203, 195, 195); */
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .dialog-cont{
    background-color: rgb(87, 85, 85);
    padding: 10px;
    border-radius: 5px;
    color: white;
  }
  .title{
    margin-right: 62px;
  }
  .desc{
    margin-right: 10px;
  }
  .desc-cont{
    word-wrap: break-word
  }
</style>
