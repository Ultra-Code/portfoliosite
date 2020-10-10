<template>
  <section class="container section mt-7">
    <div class="has-text-centered mb-6">
      <h2 class="title">About</h2>
      <h3 class="subtitle has-text-grey-light">lorem lorem suap lore alo lioom ali cat lion loia</h3>
    </div>
    <ul class="content timeline">
      <li>
        <div class="timeline-image image">
          <img class="is-rounded" src="../../assets/images/man/man_with_dog.jpg" width="128" alt />
        </div>
        <div class="timeline-panel">
          <div class="timeline-heading">
            <h4 class="title">2001-2004</h4>
            <h4 class="subtitle">Our Humble Bigining</h4>
          </div>

          <div class="timeline-body">
            <p class="has-text-grey-light">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Laudantium dicta ipsa veritatis optio consequatur sed officia molestias debitis eaque,
              distinctio dolore exercitationem, provident voluptates nisi reiciendis, tenetur enim? Nesciunt, ut.
            </p>
          </div>
        </div>
      </li>
      <li class="timeline-inverted">
        <div class="timeline-image image">
          <img class="is-rounded" src="../../assets/images/man/man_with_dog.jpg" width="128" alt />
        </div>
        <div class="timeline-panel">
          <div class="timeline-heading">
            <h4 class="title">2001-2004</h4>
            <h4 class="subtitle">Our Humble Bigining</h4>
          </div>

          <div class="timeline-body">
            <p class="has-text-grey-light">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Laudantium dicta ipsa veritatis optio consequatur sed officia molestias debitis eaque,
              distinctio dolore exercitationem, provident voluptates nisi reiciendis, tenetur enim? Nesciunt, ut.
            </p>
          </div>
        </div>
      </li>
      <li>
        <div class="timeline-image image">
          <img class="is-rounded" src="../../assets/images/man/man_with_dog.jpg" width="128" alt />
        </div>
        <div class="timeline-panel">
          <div class="timeline-heading">
            <h4 class="title">2001-2004</h4>
            <h4 class="subtitle">Our Humble Bigining</h4>
          </div>

          <div class="timeline-body">
            <p class="has-text-grey-light">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Laudantium dicta ipsa veritatis optio consequatur sed officia molestias debitis eaque,
              distinctio dolore exercitationem, provident voluptates nisi reiciendis, tenetur enim? Nesciunt, ut.
            </p>
          </div>
        </div>
      </li>
      <li class="timeline-inverted">
        <div class="timeline-image">
          <h4>
            Be Part
            <br />Of Our
            <br />Story!!
          </h4>
        </div>
      </li>
    </ul>
  </section>
</template>

<style lang="scss" scoped>
.timeline {
  position: relative;
  padding: 0;
  list-style: none;
}
.timeline::before {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 40px;
  width: 2px;
  content: '';
  margin-left: -1.5px;
  background-color: #e9ecef;
}
@media (min-width: 786px) {
  .timeline::before {
    left: 50%;
  }
}
.timeline > li {
  position: relative;
  min-height: 50px;
  margin-bottom: 50px;
}
@media (min-width: 992px) {
  .timeline > li {
    min-height: 150px;
  }
}
@media (min-width: 768px) {
  .timeline > li {
    min-height: 100px;
    margin-bottom: 100px;
  }
}
.timeline > li::after {
  clear: both;
}
.timeline > li::after,
.timeline > li::before {
  display: table;
  content: ' ';
}
.timeline > li .timeline-image {
  position: absolute;
  z-index: 100;
  left: 0;
  width: 80px;
  height: 80px;
  margin-left: 0;
  text-align: center;
  color: white;
  border: 7px solid #e9ecef;
  border-radius: 100%;
  background-color: #fed136;
}
@media (min-width: 992px) {
  .timeline > li .timeline-image {
    width: 150px;
    height: 150px;
    margin-left: -75px;
  }
}
@media (min-width: 768px) {
  .timeline > li .timeline-image {
    left: 50%;
    width: 100px;
    height: 100px;
    margin-left: -50px;
  }
}
.timeline > li .timeline-panel {
  position: relative;
  float: right;
  width: 100%;
  padding: 0 20px 0 100px;
  text-align: left;
}
@media (min-width: 992px) {
  .timeline > li .timeline-panel {
    padding: 0 20px 20px;
  }
}
@media (min-width: 768px) {
  .timeline > li .timeline-panel {
    float: left;
    width: 41%;
    padding: 0 20px 20px 30px;
    text-align: right;
  }
}
.timeline > li.timeline-inverted > .timeline-panel {
  float: right;
  padding: 0 20px 0 100px;
  text-align: left;
}
.timeline > li .timeline-image h4 {
  font-size: 10px;
  line-height: 14px;
  margin-top: 12px;
}
</style>
