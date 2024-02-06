<script>
    import nowPlaying from '../../lib/images/play-arrow.png'
</script>

<div class="container">
    <div class="HStack"> 
        <div class="VStack">
            <p class="titleTrack">
                Sample text
            </p>
            <p class="bookTrack">
                Sample text
            </p>
   

        </div>

        <div class="playback">
            <img class="arrow" src={nowPlaying} alt="">
        </div>
    </div>
</div>

<style>

    .container{
        position: absolute;
        bottom: 0%;
        background-color: gray;
        width: 100%;
    }
    
    .arrow{
        width: 60px;
        aspect-ratio: 1;

    }

    .HStack{

        display: flex;
        justify-content: center;
        align-items: center;
        

    }

    .VStack{
        color: red;
        margin-right: 20px;
    }

    .titleTrack{
        font-weight: bold;
    }
</style>