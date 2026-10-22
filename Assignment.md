Assignment 4.5 — Multi-Page College Club Websitev1. Project folder structure
Create the following files and folders:

college-club/

index.html

about.html

registration.html

contact.html

style.css

images/

favicon.png

2. index.html — Home page

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Welcome to the College Club. Discover our activities, events, and student community.">
  <title>Home | College Club</title>
  <link rel="icon" type="image/png" href="images/favicon.png">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>College Club</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="registration.html">Registration</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h2>Welcome to Our College Club!</h2>
      <p>Connect, learn, create, and grow with fellow students.</p>
      <a class="btn" href="registration.html">Join Our Club</a>
    </section>

    <section>
      <h2>Our Activities</h2>
      <div class="cards">
        <article class="card">
          <h3>Technical Events</h3>
          <p>Participate in coding competitions, workshops, and quizzes.</p>
        </article>
        <article class="card">
          <h3>Cultural Programs</h3>
          <p>Showcase your talent through music, dance, and art.</p>
        </article>
        <article class="card">
          <h3>Community Service</h3>
          <p>Work together on volunteering and campus improvement.</p>
        </article>
      </div>
    </section>

    <section>
      <h2>Upcoming Events</h2>
      <table>
        <thead>
          <tr>
            <th>Event</th>
            <th>Date</th>
            <th>Venue</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Welcome Meeting</td>
            <td>10 November</td>
            <td>Seminar Hall</td>
          </tr>
          <tr>
            <td>Tech Quiz</td>
            <td>15 November</td>
            <td>Computer Lab</td>
          </tr>
          <tr>
            <td>Cultural Fest</td>
            <td>20 November</td>
            <td>College Auditorium</td>
          </tr>
        </tbody>
      </table>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 College Club. All rights reserved.</p>
  </footer>
</body>
</html>
3. about.html — About page

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Learn about the College Club, its mission, activities, and student members.">
  <title>About Us | College Club</title>
  <link rel="icon" type="image/png" href="images/favicon.png">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>College Club</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="registration.html">Registration</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>About Our Club</h2>
      <p>
        Our College Club is a student-led community that encourages
        creativity, teamwork, leadership, and learning beyond the classroom.
      </p>
      <h3>Our Mission</h3>
      <p>
        To provide students with opportunities to develop skills,
        discover interests, and build lasting friendships.
      </p>
      <h3>What We Do</h3>
      <ul>
        <li>Organize technical workshops and competitions.</li>
        <li>Conduct cultural events and celebrations.</li>
        <li>Encourage volunteering and community service.</li>
        <li>Develop communication and leadership skills.</li>
      </ul>
    </section>

    <section>
      <h2>Club Members</h2>
      <table>
        <thead>
          <tr>
            <th>Position</th>
            <th>Member</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>President</td><td>Student A</td></tr>
          <tr><td>Vice President</td><td>Student B</td></tr>
          <tr><td>Secretary</td><td>Student C</td></tr>
          <tr><td>Event Coordinator</td><td>Student D</td></tr>
        </tbody>
      </table>
      <p>Replace the sample names with actual club member details.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 College Club. All rights reserved.</p>
  </footer>
</body>
</html>
4. registration.html — Student registration

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Register as a student member of the College Club.">
  <title>Registration | College Club</title>
  <link rel="icon" type="image/png" href="images/favicon.png">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>College Club</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="registration.html">Registration</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main>
    <section class="form-section">
      <h2>Student Club Registration</h2>
      <p>Complete the form below to express your interest in joining.</p>

      <form action="#" method="post">
        <label for="name">Full Name</label>
        <input type="text" id="name" name="name"
               placeholder="Enter your full name" required>

        <label for="email">Email Address</label>
        <input type="email" id="email" name="email"
               placeholder="Enter your email" required>

        <label for="studentid">Student ID</label>
        <input type="text" id="studentid" name="studentid"
               placeholder="Enter your student ID" required>

        <label for="department">Department</label>
        <select id="department" name="department" required>
          <option value="">Select department</option>
          <option value="computer-science">Computer Science</option>
          <option value="commerce">Commerce</option>
          <option value="science">Science</option>
          <option value="arts">Arts</option>
          <option value="other">Other</option>
        </select>

        <label for="interest">Area of Interest</label>
        <select id="interest" name="interest" required>
          <option value="">Select an activity</option>
          <option value="technical">Technical Events</option>
          <option value="cultural">Cultural Programs</option>
          <option value="sports">Sports</option>
          <option value="social">Community Service</option>
        </select>

        <label for="message">Why would you like to join?</label>
        <textarea id="message" name="message" rows="4"
                  placeholder="Tell us about your interests"></textarea>

        <button type="submit">Submit Registration</button>
      </form>
      <p>Demo only: a backend is required to save submitted registrations.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 College Club. All rights reserved.</p>
  </footer>
</body>
</html>
5. contact.html — Contact page

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Contact the College Club for membership, events, and other inquiries.">
  <title>Contact Us | College Club</title>
  <link rel="icon" type="image/png" href="images/favicon.png">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>College Club</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="registration.html">Registration</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Contact Us</h2>
      <p>Have a question or want to learn more? Get in touch with us.</p>

      <div class="card">
        <h3>Email</h3>
        <p><a href="mailto:club@example.com">club@example.com</a></p>

        <h3>Location</h3>
        <p>College Campus, Main Building, Lucknow, Uttar Pradesh</p>

        <h3>Office Hours</h3>
        <p>Monday to Friday, 10:00 AM – 4:00 PM</p>

        <h3>Contact Person</h3>
        <p>Club Secretary</p>
        <p>Phone: Replace with the official club phone number.</p>
      </div>

      <p>
        <a class="btn" href="registration.html">Become a Member</a>
      </p>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 College Club. All rights reserved.</p>
  </footer>
</body>
</html>
6. style.css — Common stylesheet

css

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #263238;
  background: #f4f7fb;
}

header {
  background: #173b6c;
  color: white;
  text-align: center;
  padding: 20px;
}

header h1 {
  margin: 0 0 12px;
}

nav {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 12px;
}

nav a {
  color: white;
  text-decoration: none;
  padding: 8px 12px;
  border-radius: 5px;
}

nav a:hover {
  background: #315b8c;
}

main {
  max-width: 1000px;
  margin: auto;
  padding: 24px;
}

section {
  background: white;
  margin-bottom: 24px;
  padding: 24px;
  border-radius: 10px;
  box-shadow: 0 2px 8px #00000010;
}

.hero {
  text-align: center;
  background: #e5efff;
  padding: 48px 24px;
}

.btn,
button {
  display: inline-block;
  background: #1769aa;
  color: white;
  padding: 11px 18px;
  border: none;
  border-radius: 5px;
  text-decoration: none;
  cursor: pointer;
  font-size: 16px;
}

.btn:hover,
button:hover {
  background: #104b7b;
}

.cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 16px;
}

.card {
  padding: 18px;
  background: #f0f5fc;
  border-radius: 8px;
  margin-bottom: 12px;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 16px;
}

th,
td {
  border: 1px solid #ccd5e0;
  padding: 12px;
  text-align: left;
}

th {
  background: #173b6c;
  color: white;
}

form {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

input,
select,
textarea {
  width: 100%;
  padding: 11px;
  border: 1px solid #b9c5d3;
  border-radius: 5px;
  font: inherit;
}

input:focus,
select:focus,
textarea:focus {
  outline: 2px solid #1769aa;
}

footer {
  background: #173b6c;
  color: white;
  text-align: center;
  padding: 16px;
}

@media (max-width: 650px) {
  .cards {
    grid-template-columns: 1fr;
  }

  main {
    padding: 14px;
  }

  section {
    padding: 16px;
  }

  table {
    font-size: 14px;
  }

  th,
  td {
    padding: 8px;
  }
}