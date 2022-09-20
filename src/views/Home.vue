<template>
  <div>
    <Hero />
    <div>
      <div class="text-center lg:mx-0 mx-6 my-5">
        <div class="text-3xl capitalize my-4 lg:mt-10">
          Browse popular Artisans on Demand
        </div>
        <div class="text-base lg:w-1/2 mx-auto">
          Here are some categories of artisans on demand. Popular artisans may
          change dependent on the demand
        </div>
      </div>
      <div class="lg:flex lg:my-0 my-10 justify-evenly lg:p-16 p-4 flex-wrap">
        <div
          class="lg:w-1/5 p-4 lg:my-0 my-8 mx-5 shadow-xl rounded-md"
          v-for="(catgory, i) in catgories"
          :key="i"
        >
          <div class="text-lg my-2 font-bold text-center" style="display: flex; justify-content: center; align-items: center; flex-direction: column;">
            <img
              class="w-10"
              src="../assets/features/tool-box.png"
              alt=""
            />
            {{ catgory.title }}
          </div>
          <div class="text-m text-center font-light text-sm">
            <p
              class="mb-2"
              v-for="(sub, i) in catgory.subs"
              :key="i"
            >{{ sub }}</p>
          </div>
        </div>
      </div>
    </div>

    <div
      id="about"
      class="lg:flex lg:m-12 m-6 lg:mx-20 justify-between"
    >
      <div class="lg:w-full my-auto">
        <div class="lg:text-6xl text-3xl my-3">What is GetArtisan?</div>
        <div class="lg:text-2xl text-thin text text-lg my-8 text-gray-500">
          About GetArtisan is an online platform that connects customers across
          the globe. We help find artisans that best deliver the services you
          need in your location of choice. Lorem ipsum dolor sit, amet
          consectetur adipisicing elit. Magni est molestiae quos repellat
          ducimus culpa dicta, voluptatum, incidunt optio, velit dignissimos
          sint fugiat laudantium!
        </div>
        <button class="
            lg:text-2xl
            bg-blue
            lg:p-4
            p-2
            rounded-md
            text-lg text-white
            mb-5
          ">
          Become an Artisian
        </button>
      </div>
      <div class="lg:w-full mt-6">
        <img
          class="ml-auto rounded-md"
          src="../assets/collage.jpg"
          alt=""
        />
      </div>
    </div>

    <div class="my-32 bg-gray-100 py-10 lg:pb-20">
      <div class="text-center lg:m-0 m-6 my-5">
        <div class="
            lg:text-5xl
            text-3xl
            font-bold
            lg:w-1/2
            mx-auto
            capitalize
            my-4
            text-blue
          ">
          Get artisan is free simple and easy to use
        </div>
      </div>
      <div class="lg:flex lg:my-0 lg:my-10 justify-evenly lg:p-16 p-4">
        <div class="lg:w-1/5 text-center lg:my-0 my-8">
          <img
            class="w-16 mx-auto"
            src="../assets/desc/booking.png"
            alt=""
          />
          <div class="text-2xl my-2 font-bold text-blue">
            Search Artisans by location
          </div>
          <div class="text-m">
            here are thousands of artisans in various locations waiting for a
            booking from you
          </div>
        </div>
        <div class="lg:w-1/5 text-center lg:my-0 my-8">
          <img
            class="w-16 mx-auto"
            src="../assets/desc/search.png"
            alt=""
          />
          <div class="text-2xl my-2 font-bold text-blue">
            Book any artisan of choice
          </div>
          <div class="text-m">
            Select from the list of artisans in your specified location.
          </div>
        </div>
        <div class="lg:w-1/5 text-center lg:my-0 my-8">
          <img
            class="w-16 mx-auto"
            src="../assets/desc/phone-call.png"
            alt=""
          />
          <div class="text-2xl my-2 font-bold text-blue">
            Recieve a call from the verified artisan
          </div>
          <div class="text-m">
            You receive a call from your selected artisan
          </div>
        </div>
      </div>
      <div class="text-center">
        <button class="bg-blue lg:p-5 p-2 text-white text-lg rounded-md">
          Get started now for free
        </button>
      </div>
    </div>

    <div class="lg:flex lg:m-12 m-6 lg:mx-20 justify-between my-20">
      <div class="lg:w-full my-auto lg:mr-4">
        <div class="lg:text-5xl lg:text-left text-center text-3xl mt-3 text-blue">
          Daily life made simpler
        </div>
        <div class="
            lg:text-xl lg:text-left
            text-center text-lg
            my-8
            text-gray-500 text
          ">
          Looking to get the job done by a genuine professional in his field?
          Search no more, We're here to simplify your search by offering the
          very best.
        </div>
        <div>
          <ul class="lg:text-2xl text-lg lg:mb-0 mb-8">
            <li class="my-2 text-gray-500 text text-xl">
              Choose from our database of verified artisans
            </li>
            <li class="my-2 text-gray-500 text text-xl">
              Schedule and fix a time that works best for you
            </li>
            <li class="my-2 text-gray-500 text text-xl">
              Discuss with the artisan and get your job done
            </li>
          </ul>
        </div>
      </div>
      <div class="lg:w-full">
        <img
          class="ml-auto"
          src="../assets/easier.png"
          alt=""
        />
      </div>
    </div>
    <div class="my-20">
      <div class="lg:text-5xl text-3xl text-center tect-blue">
        Ready to get Started?
      </div>
      <div class="lg:flex justify-evenly my-20 lg:m-0 m-4">
        <div class="w-full">
          <img
            class="lg:w-96 w-44 mx-auto"
            src="../assets/features/tool-box.png"
            alt=""
          />
          <div class="lg:w-96 mx-auto text-center text lg:text-lg text-sm">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate
            architecto obcaecati laboriosam vero nobis quaerat!
          </div>
          <div class="text-center my-4">
            <button class="bg-blue mx-auto w-44 lg:p-4 p-2 text-white rounded-md">
              Sign Up as User
            </button>
          </div>
        </div>

        <div class="w-full">
          <img
            class="lg:w-96 w-44 mx-auto"
            src="../assets/features/tool-box.png"
            alt=""
          />
          <div class="lg:w-96 mx-auto text-center text lg:text-lg text-sm">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate
            architecto obcaecati laboriosam vero nobis quaerat!
          </div>
          <div class="text-center my-4">
            <button class="bg-blue mx-auto w-44 lg:p-4 p-2 text-white rounded-md">
              Sign Up as Artisian
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import Hero from "../components/Hero.vue";

const catgories = [
  {
    image: '',
    title: 'Auto Repairs',
    subs: [
      'Car & Auto Repair',
      'Motorcycle Repair',
      'Trucks And Trailers Repair',
      'Others Auto Repairs'
    ]
  },
  {
    image: '',
    title: 'Beauty and Fashion',
    subs: [
      'Men Salon & Barber',
      'Women Salon & Hair Stylist',
      'Massage and Spa',
      'Others Beauty Services'
    ]
  },
  {
    image: '',
    title: 'Laundry and Cleaning',
    subs: [
      'Home & Office Cleaning',
      'Event Cleaning',
      'Fumigation & Pest Control',
    ]
  },
  {
    image: '',
    title: 'Home or Office',
    subs: [
      'Day Care',
      'Nanny and Baby Sitting',
      'Gardener',
      'Other Domestic Services',
    ]
  },
  {
    image: '',
    title: 'Electrical Electronics and Appliances',
    subs: [
      'Home Wiring Electrician',
      'Electronics Repair Electrician',
      'Refrigerator and AC Repairs',
      'Generator Repairs',
    ]
  },
  {
    image: '',
    title: 'Building Mechanical and Fabrication',
    subs: [
      'Welding Fabrication',
      'Carpenter & Furniture Maker',
      'Other Mechanical Services',
      'Architect',
    ]
  },
  {
    image: '',
    title: 'Event Planning',
    subs: [
      'Wedding',
      'Birthdays',
      'Conference',
      'Other Event Sevices',
    ]
  },
  {
    image: '',
    title: 'Computer Mobile and IT',
    subs: [
      'Computer Repairs',
      'Mobile Phone Repairs',
      'IT Services',
      'Other Mobile Services',
    ]
  },
]
</script>