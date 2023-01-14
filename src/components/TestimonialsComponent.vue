<template>
    <div>
      <div v-for="testimonial in testimonials" :key="testimonial.id">
        <h2>{{ testimonial.name }}</h3>
        <img>{{ testimonial.imageUrl }}
        <h3>{{ testimonial.relation }}</h3>
        <p>{{ testimonial.text }}</p>
      </div>
    </div>
  </template>
<script>

export default {
    data () {
        return{
            testimonial: [{
                id: 1,
                imgUrl: 'https://i.postimg.cc/7ZFPwC2t/Joel-Profile.jpg',
                name: 'Joel',
                relation: 'Lecture'
                text: 'Zimasile is a very innovative and a well determined student. He enjoys working with his classmates and does well working on his project. He has learned a lot about web development, including Bootstrap 5. I am quite delighted with the effort he puts into his work.'
            },
            {
                id: 2,
                imgUrl: 'https://i.postimg.cc/nccCLZbJ/candice-2022.jpg',
                name: 'Candice',
                relation: 'Academy Facilitor'
                text: 'He is very focused and goal driven. Once he sets his mind on something, he will ensure to achieve it. He is not afraid to dream big and at the same time being realistic.'
            },
            {
                id: 3,
                imgUrl: 'https://i.postimg.cc/RCJtBvBb/20220831-20-14-02.jpg',
                name: 'Tyvon',
                relation: 'classmate'
                text: 'Zimasile is a very professional person when it comes to his work. He has full understanding of what he is doing and is a very reliable person, I enjoy working with him.'
            },
            {
                id: 4,
                imgUrl: 'https://i.postimg.cc/XJXb1mPm/DSC-3622.jpg',
                name: 'Lazola',
                relation: 'classmate'
                text: 'He is a calm person and always interested in learning.'
            }]
        }
    }
}

</script>
<style>
    
</style>