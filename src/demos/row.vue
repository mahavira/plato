<template>
  <div class="d-row">
    <div>
      <c-row>
        <p>no cols</p>
      </c-row>
    </div>
    <div>
      <c-row>
        <c-col>col</c-col>
        <c-col>col</c-col>
      </c-row>
      <c-row>
        <c-col :size="1">col-1</c-col>
        <c-col :size="3">col-3</c-col>
      </c-row>
      <c-row>
        <c-col :size="3">col-3</c-col>
        <c-col :size="1">col-1</c-col>
      </c-row>
    </div>
    <div>
      <c-row>
        <c-col>col</c-col>
        <c-col>col</c-col>
        <c-col>col</c-col>
      </c-row>
      <c-row>
        <c-col :size="1">col-1</c-col>
        <c-col :size="2">col-2</c-col>
        <c-col :size="1">col-1</c-col>
      </c-row>
    </div>
    <div>
      <c-row class="padding">four rows in group with padding</c-row>
      <c-row class="padding">four rows in group with padding</c-row>
      <c-row class="padding">four rows in group with padding</c-row>
      <c-row class="padding">four rows in group with padding</c-row>
    </div>
  </div>
</template>

<script>
import CRow from 'components/c-row'
import CCol from 'components/c-col'

export default {
  components: {
    CRow,
    CCol
  }
}
</script>

<style src="styles/demo"></style>
