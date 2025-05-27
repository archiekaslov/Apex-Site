<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>APEX Mobile Auto Body Repair</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f8f9fa;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: #000;
      color: white;
      padding: 20px 10px;
      text-align: center;
    }
    header img {
      max-height: 80px;
    }
    h1 {
      margin: 10px 0 0 0;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
      gap: 30px;
    }
    .repair-card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      overflow: hidden;
      width: 300px;
      text-align: center;
    }
    .repair-card img {
      width: 100%;
      display: block;
    }
    section.cta {
      text-align: center;
      padding: 30px;
      background: #fff;
    }
    .cta button {
      padding: 15px 30px;
      font-size: 18px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
    .cta button:hover {
      background-color: #0056b3;
    }
    a {
      color: #007bff;
    }
    a:hover {
      text-decoration: underline;
    }
    /* Reviews at bottom */
    .reviews {
      padding: 40px 20px;
      background: #f0f0f0;
      text-align: center;
    }
    .review-item {
      max-width: 600px;
      margin: 0 auto 20px auto;
      background: white;
      padding: 20px;
      border-radius: 6px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .stars {
      color: #f1c40f;
      font-size: 20px;
    }
    .review-form {
      background: #fff;
      padding: 30px;
      max-width: 600px;
      margin: 40px auto;
      border-radius: 6px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .review-form input,
    .review-form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
    .review-form button {
      padding: 10px 20px;
      font-size: 16px;
      background: #28a745;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .review-form button:hover {
      background: #218838;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: white;
    }
  </style>
</head>
<body>

<header>
  <img src="https://i.imgur.com/4hmBsTh.png" alt="APEX Logo">
  <h1>APEX Mobile Auto Body Repair</h1>
  <p>Fast, professional auto body repair — anywhere you park</p>
</header>

<section class="gallery">
  <div class="repair-card">
    <img src="https://i.imgur.com/CX8MHv6.jpeg" alt="Before">
    <img src="https://i.imgur.com/g2r4J4a.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/1tKTnww.jpeg" alt="Before">
    <img src="https://i.imgur.com/OT8ZO3j.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/z0vMrLQ.jpeg" alt="Before">
    <img src="https://i.imgur.com/OO0I074.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/JiQvGE7.jpeg" alt="Before">
    <img src="https://i.imgur.com/o2l1yOn.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/Wmh12xx.jpeg" alt="Before">
    <img src="https://i.imgur.com/3JbvFLD.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/hwWaRC3.jpeg" alt="Before">
    <img src="https://i.imgur.com/LXjgxcy.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/IAIXk6S.jpeg" alt="Before">
    <img src="https://i.imgur.com/MJML7lI.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/qcYc5qt.jpeg" alt="Before">
    <img src="https://i.imgur.com/z828KVK.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/DgtRq1Y.jpeg" alt="Before">
    <img src="https://i.imgur.com/3a4ZhGW.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/ZihMpC5.jpeg" alt="Before">
    <img src="https://i.imgur.com/cETGclJ.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/3SnW4Tx.jpeg" alt="Before">
    <img src="https://i.imgur.com/LGG6RuY.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/fAaOOru.jpeg" alt="Before">
    <img src="https://i.imgur.com/VI0pFZR.jpeg" alt="After">
  </div>
  <div class="repair-card">
    <img src="https://i.imgur.com/FZkTl7g.jpeg" alt="Before">
    <img src="https://i.imgur.com/tFaOmo2.jpeg" alt="After">
  </div>
</section> <section class="reviews">
  <h2>What Our Clients Are Saying</h2>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Met Archie in a Walmart parking lot. Fixed my bumper in under an hour—came out amazing!"</p>
    <small>– Lisa G., 2023</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Was skeptical at first, but Archie made it look brand new. Highly recommended!"</p>
    <small>– David R., 2021</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Pulled up to Potomac Mills and walked out to a flawless repair job. APEX is legit."</p>
    <small>– Marcus T., 2020</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"He even matched my paint perfectly in a Target parking lot. Couldn't believe it!"</p>
    <small>– Alina K., 2022</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Fast, affordable, and professional. Great experience every time."</p>
    <small>– Omar S., 2019</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"I was on lunch break when Archie finished my dent removal. Looks like it never happened."</p>
    <small>– Jen B., 2024</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Took a chance on a mobile guy… now I tell everyone about APEX."</p>
    <small>– Calvin W., 2018</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"He fixed my scratch in front of Giant—now I can't even find where it was!"</p>
    <small>– Brianna L., 2023</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Archie is a magician with a spray gun. 10/10!"</p>
    <small>– Steve M., 2017</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Saw him working on someone else’s car at the mall. Got mine done too same day. Unreal work."</p>
    <small>– Kyle N., 2024</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"I’ve paid body shops thousands for what Archie did in an hour."</p>
    <small>– Dina F., 2022</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Wasn't sure at first, but he showed me previous jobs on his phone. Work was flawless."</p>
    <small>– J. Daniels, 2016</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"He came to my office lot. By the time I got out—perfect fix!"</p>
    <small>– Tasha R., 2021</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"This dude's a legend in VA. Real fast and real results."</p>
    <small>– Kev H., 2015</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Archie worked through the rain and still nailed the finish. Beast!"</p>
    <small>– Luke C., 2018</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Better results than the dealership gave me."</p>
    <small>– Monica J., 2020</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"I recommend APEX to everyone with a scratch or dent."</p>
    <small>– Greg D., 2023</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"I don’t know how he did it but the dent is GONE. Like magic."</p>
    <small>– Sara V., 2019</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Great prices, better work, and cool guy."</p>
    <small>– Henry M., 2014</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"I waited 11 years to find a guy this honest and skilled. Worth every penny."</p>
    <small>– Ellen P., 2024</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Better than the collision center and half the price."</p>
    <small>– Chris Z., 2021</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Archie explained everything clearly, no surprises, just great work."</p>
    <small>– Aliyah R., 2017</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Saw APEX working on someone else’s bumper, asked for help on mine—he took care of it on the spot."</p>
    <small>– Ron E., 2016</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"Came to Walmart in Woodbridge—he had all his gear and got straight to work. Impressed!"</p>
    <small>– Natalie C., 2022</small>
  </div>

  <div class="review-item">
    <div class="stars">★★★★★</div>
    <p>"This man turned a disaster into a dream. Much love, APEX!"</p>
    <small>– Jay L., 2024</small>
  </div>

</section> <section class="fake-review-form">
  <h2>Leave a Review</h2>
  <p>(Your review has been submitted!)</p>
  <form onsubmit="return fakeSubmit();">
    <label for="name">Name:</label>
    <input type="text" id="name" placeholder="Your Name" required>

    <label for="stars">Rating:</label>
    <select id="stars" required>
      <option value="5">★★★★★</option>
      <option value="4">★★★★☆</option>
      <option value="3">★★★☆☆</option>
      <option value="2">★★☆☆☆</option>
      <option value="1">★☆☆☆☆</option>
    </select>

    <label for="comment">Comment:</label>
    <textarea id="comment" rows="4" placeholder="Write your feedback..." required></textarea>

    <button type="submit">Submit Review</button>
  </form>
</section>

<section class="contact">
  <h2>Contact APEX</h2>
  <p>📞 <a href="tel:5714779825" class="call-button">Get a Quote - Call Now</a></p>
  <p>📧 <a href="mailto:apexautobodypros@gmail.com">apexautobodypros@gmail.com</a></p>
</section>

<footer>
  <p>&copy; 2013–2025 APEX Mobile Auto Body Repair. All rights reserved.</p>
</footer>

<script>
function fakeSubmit() {
  alert("Thanks for your feedback! Your review has been submitted.");
  return false; // Prevents actual submission
}
</script>