<p>Second Component</p>

<ul>
  {#each pipes as pipe}
    <li>{pipe.foo}</li>
  {/each}
</ul>

<script>
  export default {
    data () {
      return {
        pipes: [
          { foo: 'bar' },
          { foo: 'baz' }
        ]
      }
    }
  }
</script>