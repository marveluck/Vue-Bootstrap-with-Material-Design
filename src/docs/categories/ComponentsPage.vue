<template>
  <mdb-container>
    <mdb-row>
      <mdb-col md="8" class="mx-auto">
        <mdb-jumbotron class="mt-5">
          <h1 class="pb-2"><mdb-icon icon="cubes" class="grey-text mr-2" />Components</h1>
          <h6 class="my-3">FREE</h6>
          <mdb-list-group>
            <!-- FREE -->
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/alert">
              <h5 class="justify-content-between d-flex align-items-center">
                Alerts<mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/badge">
              <h5 class="justify-content-between d-flex align-items-center">
                Badge<mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/button">
              <h5 class="justify-content-between d-flex align-items-center">
                Button <mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/card">
              <h5 class="justify-content-between d-flex align-items-center">
                Cards <mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/dropdown">
              <h5 class="justify-content-between d-flex align-items-center">
                Dropdown <mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/edge-header">
              <h5 class="justify-content-between d-flex align-items-center">
                Edge Header <mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/iframe">
              <h5 class="justify-content-between d-flex align-items-center">
                iFrame<mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/listgroup">
              <h5 class="justify-content-between d-flex align-items-center">
                List Group <mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/media">
              <h5 class="justify-content-between d-flex align-items-center">
                Media <mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/pagination">
              <h5 class="justify-content-between d-flex align-items-center">
                Pagination <mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/panel">
              <h5 class="justify-content-between d-flex align-items-center">
                Panels <mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/progress-bars">
              <h5 class="justify-content-between d-flex align-items-center">
                Progress Bar <mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>
            <mdb-nav-item class="list-group-item list-group-item-action" router href="/components/slider">
              <h5 class="justify-content-between d-flex align-items-center">
                Slider <mdb-icon icon="angle-right"/>
              </h5>
            </mdb-nav-item>

          </mdb-list-group>
        </mdb-jumbotron>
      </mdb-col>
    </mdb-row>
  </mdb-container>
</template>

<script>
import { mdbContainer, mdbRow, mdbCol, mdbIcon, mdbJumbotron, mdbNavItem, mdbListGroup } from 'mdbvue';

export default {
  name: 'ComponentsPage',
  components: {
    mdbContainer,
    mdbRow,
    mdbCol,
    mdbIcon,
    mdbJumbotron,
    mdbNavItem,
    mdbListGroup
  }
};
</script>

<style scoped>
.example-components-list {
  padding-top: 20px;
}

.example-components-list li {
  padding: 10px;
  background-color: white;
  border-bottom: 1px solid #f7f7f7;
  transition: .3s;
}

.example-components-list h6 {
  padding: 20px 10px 5px 10px;
  color: grey;
}

.example-components-list li:hover {
  background-color: #fafafa;
}

.example-components-list i {
  float: right;
  padding-top: 3px;
}

.nav-link.navbar-link h5 {
  color: #212529;
}
</style>
