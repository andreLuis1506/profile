<script lang="ts">
	const profileImg:string  = 'image/profile.png'
</script>

<div class="profile-container">
  <img src={profileImg} alt="">
</div>


<style>
  .profile-container{
    width: 220px;
    height: 220px;
    border-radius: 50%;
    overflow: hidden;
    background-color: #ffc740;
    display: flex;
    align-items: end;
    justify-content: center;
  }

</style>