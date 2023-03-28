<template>
    <div class="main">
        <section class="about" id="about">

            <div class="image">
                <img src="images/image1.gif" alt="">
            </div>

            <div class="content">
                <h3>Why you should <span class="line-down">choose us?</span></h3>
                    <p>Sunrise Solar is a specialist solar panel installation company for the commercial, public sector, agricultural and domestic markets. We provide a 
                        professional and personal service for the supply of solar photovoltaic systems to all sectors. <br><br>
                        Whether it be a simple domestic installation or a multi-site commercial project, Sunrise Solar has the technical expertise and resources to deliver 
                        complex projects on time and to a very high standard. Our typical customers are businesses, construction companies, county & city councils, farmers, 
                        schools, and the general public. Our capabilities include all types of pitch roof-mounted solar panels, flat roof solar panel installations 
                        ground-mounted solar. 
                    </p>
                <a href="#" class="btn">read more</a>
            </div>
        </section>

    </div>


</template>

<style scoped>
section{
    background-color: rgba(128, 128, 128, 0.288);
}
.about {
  min-height: 85vh;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -ms-flex-wrap: wrap;
      flex-wrap: wrap;
  gap: 2rem;
}

.about .image {
  -webkit-box-flex: 1;
      -ms-flex: 1 1 42rem;
          flex: 1 1 42rem;
}

.about .image img {
  width: 100%;
}

.about .content {
  -webkit-box-flex: 1;
      -ms-flex: 1 1 42rem;
          flex: 1 1 42rem;
}

.about .content h3 {
  font-size: 4rem;
  line-height: 1.5;
}

.about .content p {
  font-size: 1.7rem;
  line-height: 2;
  padding: 1rem 0;
  color: gray;
}

</style>