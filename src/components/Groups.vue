<template>
  <div>
    <li v-for="group in groups" v-bind:key="group.id">
    {{ group.name }}
    </li>
  </div>
</template>

<script>

import {groupList} from "../data/groups";

export default {
  name: 'Groups',
  data: function () {
		return {
			groups: groupList,
		}
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>