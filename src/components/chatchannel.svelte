<nav class="chatchaneel">
    <div>

      <div>
        <form>
          <input type="text" class="searchbar" placeholder="search people" name="search">
          
        </form>
      </div>

      <div class="quickacessheadspacearea"></div>
      <div class="quickacess"> 

      <a class="channelprofile"> 
        <div class="avatarpicture" role="img"> 
          <img src=../static/image/image1.jpeg class="avatarpicturecircle" width="48px" hieght="48px" > 
        </div>
        <div class="friendsusername">Home</div>
      </a>

      <a class="channelprofile" onclick="document.location.href='/message';"> 
        <div class="avatarpicture" role="img"> 
          <img src=../static/image/image1.jpeg class="avatarpicturecircle" width="48px" hieght="48px" > 
        </div>
        <div class="friendsusername">Message</div>
      </a>

      <button class="channelprofile" type="button">
        create post
      </button>

      <hr>
      </div>

      <a class="channelprofile"> 
        <div class="avatarpicture" role="img"> 
          <img src=../static/image/image1.jpeg class="avatarpicturecircle" width="48px" hieght="48px" > 
        </div>
        <div class="friendsusername">Quax</div>
      </a>

      <a class="channelprofile"> 
        <div class="avatarpicture" role="img"> 
          <img src=../static/image/image1.jpeg class="avatarpicturecircle" width="45px" hieght="45px" > 
        </div>
        <div class="friendsusername">Quax</div>
      </a>

    </div>
  </nav>

<style>
.chatchaneel {
  margin: 0;
  padding: 0;
  display: flex;
  overflow: hidden;
  flex-direction: column;
  box-sizing: border-box;
  /* background-color: #2d3436; */
  /* background-image: linear-gradient(315deg, #2d3436 0%, #000000 74%); */
  background-color: rgb(26, 62, 116);
  max-width: 225px;
  position: fixed;
  transform: translate(32%, 0%);
  height: 100%;
  width: 225px;
  overflow-y: hidden;
  float: left;
}

.channelprofile {
  margin-left: 8px;
  display: flex;
  box-sizing: border-box;
  border-radius: 4px;
  outline: 0;
  margin-right: 12px;
  max-width: 224px;
  background-color: var(--gray4);
  height: 48px;
  margin-bottom: 15px;
  cursor: pointer;
}

.avatarpicture{
  padding-left:10px;
  display: flex;
  position: relative;
  width: 48px;
  height: 48px;
}

.searchbar{
    position: relative;
    width: 200px;
    height: 28px;
    top: 20px;
    left: 10px;
    border-radius: 8px;
}


</style>