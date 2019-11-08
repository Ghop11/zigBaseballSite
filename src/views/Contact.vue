<template>
  <div>
    <br>
    <v-spacer>
      <center>
        <v-flex>
          <v-card max-width="500px">
            <v-simple-table>
              <thead>
              <th class="text-left" style="font-size: 25px"><b>Contact Info</b></th>
              </thead>
              <tbody>
              <tr>
                <td class="text-left">Main Number: </td>
                <td class="text-left">555-555-5555</td>
              </tr>
              <tr>
                <td>Email: </td>
                <td>email@gmail.com</td>
              </tr>
              <tr>
                <td>Other info: </td>
                <td>Details</td>
              </tr>
              </tbody>
            </v-simple-table>
          </v-card>
        </v-flex>
      </center>
    </v-spacer>

  </div>
</template>

<script>
    export default {
        name: "contact.vue"
    }
</script>

<style scoped>

</style>