<template>
<div className='App'>
<h1>Monsters Rolodex</h1>
<Search handleSearch={handleSearch} />
<CardList monsters={filteredMonsters} />  
</div>  
</template>

<script>
export default {
  name:'Home',
}
</script>

<style>
h1{
  font-family: 'Bigelow Rules';
  font-size: 72px;
  color: #0ccac4;
  background-image:darkcyan ;
   }
.App{
  text-align: center;
   }
</style>
