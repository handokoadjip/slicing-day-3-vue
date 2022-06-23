<template>
  <section v-for="(list, index) in lists" :key="index" :id="list.title">
    <div class="container-fluid">
      <div class="row min-vh-100">
        <div class="col-lg-6" :class="[list.image, {'order-0 order-lg-1': index % 2 === 0}]"></div>
        <div class="col-lg-6 d-flex justify-content-center align-items-center"
          :class="{'order-1 order-lg-0': index % 2 === 0}">
          <div class="wrapper text-center">
            <h2 class="display-5 text-border-bottom-center text-uppercase mb-5">{{ list.title }}</h2>
            <p class="ff-brygada w-75 ls-1 leading-loose mb-5 mx-auto">{{ list.description }}</p>
            <router-link class="btn-custom ls-1 text-center d-block position-relative mx-auto" :to="list.href">Add to cart</router-link>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContentComponent",
  data() {
    return {
      lists: [
        {
          image: "bg-image-1",
          title: "philip",
          description:
            "A tropical leaf, with delightful shapes perfect for offices and workpaces",
          href: "#",
        },
        {
          image: "bg-image-2",
          title: "olivia",
          description:
            "A tropical leaf, with delightful shapes perfect for offices and workpaces",
          href: "#",
        },
        {
          image: "bg-image-3",
          title: "grace",
          description:
            "A tropical leaf, with delightful shapes perfect for offices and workpaces",
          href: "#",
        },
      ]
    }
  }
}
</script>