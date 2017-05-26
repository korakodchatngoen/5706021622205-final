<template>
  <div>
    <div class="columns">
      <div class="column is-half is-offset-one-quarter">
        <br><br>
        <div class="columns">
          <div class="column is-2">
            <div class="field">
               <label class="label">ปี</label>
              <p class="control">
                <span class="select">
                  <select>
                    <option>1</option>
                    <option>2</option>
                    <option>3</option>
                    <option>4</option>
                    <option>5</option>
                    <option>6</option>
                    <option>7</option>
                    <option>8</option>
                  </select>
                </span>
              </p>
            </div>
          </div>
          <div class="column is-2">
              <div class="field">
                 <label class="label">ภาคเรียน</label>
                <p class="control">
                  <span class="select">
                    <select>
                      <option>1</option>
                      <option>2</option>
                      <option>3</option>
                    </select>
                  </span>
                </p>
              </div>
          </div>
        </div>
        <div class="columns">
          <div class="column is-6">
             <label class="label">วิชา</label>
            <input class="input" type="text">
          </div>
          <div class="column is-2">
             <label class="label">หน่วยกิต</label>
            <input class="input" type="text">
          </div>
          <div class="column is-2">
             <label class="label">เกรด</label>
            <input class="input" type="text">
          </div>
        </div>
        <div class="columns">
          <div class="column is-half is-offset-one-quarter">
            <button class="button is-primary" >Add</button>
          </div>
        </div>
      </div>
    </div>
</div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
