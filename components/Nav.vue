<template>
    <div >
  <b-navbar style="backgroundColor: #ffff" toggleable="lg" >
    <NuxtLink to="/">
    <b-navbar-brand href="/">
        <img :src="require(`@/assets/logo.png`)" alt="" >
    </b-navbar-brand>
    </NuxtLink>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="nav_item">
        <NuxtLink to="/"><b-nav-item href="/" >Home</b-nav-item></NuxtLink>
        <b-nav-item-dropdown text="About Us" right>
          <NuxtLink to="/about_us/whybizzcon"><b-dropdown-item href="/about_us/whybizzcon" style="color: #ffff" >Why Bizzcon</b-dropdown-item></NuxtLink>
          <NuxtLink to="/about_us/leaders"><b-dropdown-item href="/about_us/leaders">Leadership Team</b-dropdown-item></NuxtLink>
          <NuxtLink to="/about_us/board"><b-dropdown-item href="/about_us/board">Supervisory Board</b-dropdown-item></NuxtLink>
          <!--<NuxtLink to="/about_us/whybizzcoin"><b-dropdown-item href="#">Media</b-dropdown-item></NuxtLink> -->
          <NuxtLink to="/about_us/life"><b-dropdown-item href="/about_us/life" >Life at BCS</b-dropdown-item></NuxtLink>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="Services" right>
          <b-dropdown-item href="#">Executive Search</b-dropdown-item>
          <b-dropdown-item href="#">Senior and Middle Level Hiring</b-dropdown-item>
          <b-dropdown-item href="#">Recruitment Process Outsourcing</b-dropdown-item>
          <b-dropdown-item href="#">Global Sourcing</b-dropdown-item>
        </b-nav-item-dropdown>
        <NuxtLink to="/industries"><b-nav-item href="/industries">Industry Practices</b-nav-item></NuxtLink>

        <b-nav-item-dropdown text="Jobs" right>
          <NuxtLink to="/jobs/post"><b-dropdown-item href="/jobs/post">Submit your CV</b-dropdown-item></NuxtLink>
          <NuxtLink to="/jobs/search"><b-dropdown-item href="/jobs/search">Job Search</b-dropdown-item></NuxtLink>

        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="Insights" right>
          <b-dropdown-item href="#">Webinar</b-dropdown-item>
          <b-dropdown-item href="#">Whitepaper</b-dropdown-item>
          
        </b-nav-item-dropdown>
        <NuxtLink to="/contact_us"><b-nav-item href="/contact_us">Contact Us</b-nav-item></NuxtLink>

      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <!-- <b-navbar-nav class="ml-auto"> -->
        <!-- <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form> -->

        <!-- <b-nav-item-dropdown text="Lang" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown> -->

        <!-- <b-nav-item-dropdown right>
          <template #button-content>
            <em>User</em>
          </template>
          <b-dropdown-item href="#">Profile</b-dropdown-item>
          <b-dropdown-item href="#">Sign Out</b-dropdown-item>
        </b-nav-item-dropdown> -->
      <!-- </b-navbar-nav> -->
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
b-nav-item{
  color: black;
}
</style>