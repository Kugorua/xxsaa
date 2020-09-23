<template>
  <div class="app">
    <Header />
    <Banner />
    <Form />
    <Product />
    <Introduces />
    <Support />
    <IntroduceStaff />
    <Information />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header";
import Banner from "./components/banner/Banner";
import Form from "./components/form/Form";
import Product from "./components/product/Product";
import Introduces from "./components/introduce/Introduces";
import Support from "./components/support/Support";
import IntroduceStaff from "./components/introduce-staff/IntroduceStaff";
import Information from "./components/information/Information";
import Footer from "./components/footer/footer";
export default {
  name: "App",
  components: {
    Header,
    Banner,
    Form,
    Product,
    Introduces,
    Support,
    IntroduceStaff,
    Information,
    Footer
  }
};
</script>

<style></style>
