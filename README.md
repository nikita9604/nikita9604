<img src="https://github.com/nikita9604/nikita9604/blob/master/image.PNG">

<p align = "center">
I am a 3rd Year undergraduate student pursuing B.Tech in Electronics and Computer Engineering<br>at Vellore Institute of Technology, Chennai, India.
</p>
<p align = "center">
I am interested in Computer Vision, Machine Learning and Data Analytics 💻. I am currently a PRISM Developer at Samsung R&D India. 
I am passionately curious, detailed-oriented and a committed engineer. I like to constantly challenge myself and take up new things from learning a new programming language to doing something different than usual.
</p>
<p align = "center">
<I>“There are some people who live in a dream world, and there are some who face reality; and then there are those who turn one into the other.”</I> 
  <p align = "right"><I> - It starts with a step 😊 </I><p>
</p>

<p align = "center">
<img align="center" height="160" width="400" src="https://github-readme-stats.vercel.app/api?username=nikita9604&theme=nightowl&show_icons=true" />
<img align="center" height="160" width="400" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nikita9604&layout=compact" />
</p>

<br>

- Github &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; : 'https://github.com/nikita9604'
      
- LinkedIn &nbsp; &nbsp; &nbsp;&nbsp; : 'https://www.linkedin.com/in/nikita-rath'

- HackkerRank : 'https://www.hackerrank.com/nikitarath01'
      
- YouTube &nbsp; &nbsp; &nbsp; &nbsp;: 'www.youtube.com/c/NIKITARATH'

<p align = "center">
  <I><B>Let's connect, explore and enjoy! Open to anything under the sky.</B></I>
</p>

<?php
    // Get access to $post object
    global $post;
    
    // Get twitter handle
    $twitter = get_field('twitter', 'options');
    
    // define links
    $links = array(
        'facebook' => 'https://www.facebook.com/sharer/sharer.php?u=' . get_permalink(),
        'twitter'  => 'https://twitter.com/intent/tweet?text='. get_the_title() .'&url='. get_permalink() .'&via='. $twitter,
        'mail'     => 'mailto:?subject='. get_the_title() .'&body=Take a look at this link - ' . get_permalink(),
        'linkedin' => 'https://www.linkedin.com/shareArticle?mini=true&url='. get_permalink() .'&title='. get_the_title() .'&summary=' . get_the_excerpt(),
        'gplus'    => 'https://plus.google.com/share?url=' . get_permalink()
    );
?>

<nav class="share" role="menu" aria-label="Share Links">
    <li class="share__item">
        <a href="<?php echo $links['facebook']; ?>" class="share__link"><span class="icon icon--xlarge icon--social-fb"></span><span class="is-hidden">Share this Post on Facebook</span></a>
    </li>
    <li class="share__item">
        <a href="<?php echo $links['twitter']; ?>" class="share__link"><span class="icon icon--xlarge icon--social-tw"></span><span class="is-hidden">Share this Post on Twitter</span></a>
    </li>
    <li class="share__item">
        <a href="<?php echo $links['mail']; ?>" class="share__link"><span class="icon icon--xlarge icon--social-mail"></span><span class="is-hidden">Share this Post via Email</span></a>
    </li>
    <li class="share__item">
        <a href="<?php echo $links['linkedin']; ?>" class="share__link"><span class="icon icon--xlarge icon--social-li"></span><span class="is-hidden">Share this Post on Linked In</span></a>
    </li>
    <li class="share__item">
        <a href="<?php echo $links['gplus']; ?>" class="share__link"><span class="icon icon--xlarge icon--social-gp"></span><span class="is-hidden">Share this Post on Google Plus</span></a>
    </li>
</nav>
