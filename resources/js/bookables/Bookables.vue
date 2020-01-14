<template>
  <div>
    <bookable-list-item
      item-title="A cheap Villa"
      item-content="A very cheap villa"
      v-bind:price="1000"
    ></bookable-list-item>
    <bookable-list-item
      item-title="A cheap Villa 2"
      item-content="A very cheap villa 2"
      :price="1500"
    ></bookable-list-item>
  </div>
</template>

<script>
import BookableListItem from "./BookableListItem";

export default {
  components: {
    BookableListItem
  }
};
</script>
