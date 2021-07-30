# What to work on
> Oh look, dynamic views! 🎑

So, this nifty section features a dynamic view that mentions what stuff needs to be worked on and if someone is assigned to it already 😄

If you want to work on something that hasn't yet been assigned (or has been assigned to Exerra), [x] 😊<br>
I, the great Queen Exerra, cannot do a lot of this stuff alone nowadays since I have a lot of other projects to work on, so I'm relying on YOU! 😆

<img src="https://techcrunch.com/wp-content/uploads/2015/04/uncle-sam-we-want-you1-kopie_1.png?w=730&crop=1" alt="drawing" width="500"/>
<br>
<br>
<br>

<div id="todo">
  <table>
    <tr>
      <th>Name</th>
      <th>Description</th>
      <th>Importance</th>
      <th>Assigned person</th>
    </tr>
    <tr v-for="todo in thingstodoarray">
      <th>{{todo.name}}</th>
      <th>{{todo.description}}</th>
      <th>{{todo.importance}}</th>
      <th v-if="todo.assigned_person !== 'None'"><a v-bind:href="'https://github.com/' + todo.assigned_person">@{{todo.assigned_person}}</a></th>
      <th v-else>{{todo.assigned_person}}</th>
    </tr>
  </table>
</div>