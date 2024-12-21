# Ex09 Event Registration Web Application
# Date:21/12/2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
DEVELOPED BY : SUDHARSAN S

REG NO: 24009664

```
<style>
.sports-container {
  border-radius: 35px;
  display: flex;
  max-width: 379px;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  color: rgba(0, 0, 0, 1);
  padding: 28px 0 149px;
  font: 400 24px JetBrains Mono, sans-serif;
}

.header-logo {
  aspect-ratio: 5.03;
  object-fit: contain;
  object-position: center;
  width: 100%;
}

.event-logo {
  aspect-ratio: 1.19;
  object-fit: contain;
  object-position: center;
  width: 142px;
  border-radius: 25px;
  margin-top: 65px;
  max-width: 100%;
}

.content-wrapper {
  align-self: stretch;
  display: flex;
  margin-top: 48px;
  width: 100%;
  flex-direction: column;
  align-items: center;
  padding: 0 51px 0 14px;
}

.event-title {
  align-self: start;
}

.login-button {
  text-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  background-color: rgba(247, 248, 180, 1);
  box-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  margin-top: 25px;
  width: 149px;
  max-width: 100%;
  white-space: nowrap;
  padding: 5px 30px 26px;
  cursor: pointer;
}

.register-button {
  text-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  background-color: rgba(240, 223, 155, 1);
  margin-top: 37px;
  width: 149px;
  max-width: 100%;
  white-space: nowrap;
  padding: 10px 17px;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="sports-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/470078989f7740e3b5c959d0153ce29f/63b48420b3beb841dd08eb4a61774d17721c91718b018c998b71c470781885a5?apiKey=470078989f7740e3b5c959d0153ce29f&"
    class="header-logo"
    alt="Sports Day Event Header"
  />
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/470078989f7740e3b5c959d0153ce29f/b3a6fb7084add2fccc8c1915938ea8cbffa5b70a678c2ee15b11a2656c83ef33?apiKey=470078989f7740e3b5c959d0153ce29f&"
    class="event-logo"
    alt="Sports Day Event Logo"
  />
  <div class="content-wrapper">
    <h1 class="event-title">SPORTS DAY EVENT</h1>
    <button class="login-button" tabindex="0">LOGIN</button>
    <button class="register-button" tabindex="0">REGISTER</button>
  </div>
</div>


<style>
.sports-events-container {
  border-radius: 35px;
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  max-width: 381px;
  flex-direction: column;
  overflow: hidden;
  font: 600 24px Inter, sans-serif;
}

.events-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  aspect-ratio: 0.581;
  gap: 1px;
  padding: 50px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.secondary-image {
  aspect-ratio: 0.11;
  object-fit: contain;
  object-position: center;
  width: 1px;
  align-self: start;
  margin-top: 161px;
}

.events-list {
  position: relative;
  text-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  flex-grow: 1;
  width: 279px;
  flex-basis: auto;
}

.event-text {
  font-family: Istok Web, sans-serif;
  font-weight: 700;
}
</style>

<div class="sports-events-container">
  <div class="events-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/470078989f7740e3b5c959d0153ce29f/fd8adf5d69540b43e14f03ca363c65cb80857578ef6c036eaf8838b6a57eab6f?apiKey=470078989f7740e3b5c959d0153ce29f&"
      class="background-image"
      alt="Sports day events background"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/470078989f7740e3b5c959d0153ce29f/ef5aa96d079e8152d553c352514fa07a3ffcc5d505dd100d38e240f01fe44fe1?apiKey=470078989f7740e3b5c959d0153ce29f&"
      class="secondary-image"
      alt=""
    />
    <div class="events-list">
      <br />
      <span class="event-text">SPORTS DAY EVENTS   &gt; Cricket</span>
      <br />
      <span class="event-text">&gt; Basket Ball</span>
      <br />
      <br />
      <span class="event-text">&gt; Foot Ball</span>
      <br />
      <span class="event-text">&gt; Volley Ball</span>
      <br />
      <span class="event-text">&gt; 100 Mts</span>
      <br />
      <span class="event-text">&gt; 200Mts</span>
      <br />
      <span class="event-text">&gt; 400Mts</span>
      <br />
      <span class="event-text">&gt; Relay</span>
    </div>
  </div>
</div>


<style>
  .visually-hidden {
    clip: rect(0 0 0 0);
    clip-path: inset(50%);
    height: 1px;
    overflow: hidden;
    position: absolute;
    white-space: nowrap;
    width: 1px;
  }

  .registration-container {
    border-radius: 35px;
    background-color: #fff;
    display: flex;
    max-width: 389px;
    flex-direction: column;
    overflow: hidden;
    color: #000;
    font: 700 10px Inter, sans-serif;
  }

  .registration-wrapper {
    display: flex;
    flex-direction: column;
    position: relative;
    aspect-ratio: 0.593;
    width: 100%;
    align-items: start;
    padding: 48px 0 90px 14px;
  }

  .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }

  .form-title {
    position: relative;
    text-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
    font-size: 24px;
    font-weight: 600;
    margin: 0 0 0 14px;
  }

  .form-field {
    position: relative;
    background-color: #fdfdfd;
    margin-top: 15px;
    padding: 7px 9px;
  }

  .field-fullname {
    width: 198px;
  }

  .field-gender {
    width: 109px;
  }

  .field-age {
    width: 92px;
  }

  .field-regnum {
    width: 168px;
  }

  .field-department {
    width: 127px;
  }

  .field-mobile {
    width: 209px;
    margin-top: 60px;
  }

  .field-email {
    width: 151px;
    background-color: #fbfbfb;
  }

  .field-events {
    width: 197px;
    background-color: #faf8f8;
    font-weight: 600;
  }

  .submit-button {
    position: relative;
    background-color: #6fe8f5;
    box-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
    align-self: center;
    margin-top: 47px;
    width: 191px;
    padding: 10px 36px;
    font-size: 24px;
    font-weight: 900;
    border: none;
    cursor: pointer;
  }

  .submit-button:hover {
    opacity: 0.9;
  }

  .submit-button:focus {
    outline: 2px solid #000;
    outline-offset: 2px;
  }
</style>

<div class="registration-container">
  <form class="registration-wrapper">
    <img
      class="background-image"
      src="https://cdn.builder.io/api/v1/image/assets/470078989f7740e3b5c959d0153ce29f/52f5fdd076a0b0e84ab4c90ffcf320828b005d0acd2c374be5e2db3d677cfa0a?apiKey=470078989f7740e3b5c959d0153ce29f&"
      alt=""
      loading="lazy"
    />
    <h1 class="form-title">EVENT REGISTRATION FORM</h1>
    
    <label for="fullname" class="visually-hidden">Full Name</label>
    <input type="text" id="fullname" class="form-field field-fullname" placeholder="FULL NAME :" required />
    
    <label for="gender" class="visually-hidden">Gender</label>
    <select id="gender" class="form-field field-gender" required>
      <option value="">GENDER :</option>
      <option value="male">Male</option>
      <option value="female">Female</option>
      <option value="other">Other</option>
    </select>
    
    <label for="age" class="visually-hidden">Age</label>
    <input type="number" id="age" class="form-field field-age" placeholder="AGE :" required />
    
    <label for="regnum" class="visually-hidden">Registration Number</label>
    <input type="text" id="regnum" class="form-field field-regnum" placeholder="REGISTRATION NUMBER :" required />
    
    <label for="department" class="visually-hidden">Department</label>
    <input type="text" id="department" class="form-field field-department" placeholder="DEPARTMENT :" required />
    
    <label for="mobile" class="visually-hidden">Mobile Number</label>
    <input type="tel" id="mobile" class="form-field field-mobile" placeholder="MOBILE NUMBER :" required />
    
    <label for="email" class="visually-hidden">Email ID</label>
    <input type="email" id="email" class="form-field field-email" placeholder="EMAIL ID :" required />
    
    <label for="events" class="visually-hidden">Events to Register</label>
    <select id="events" class="form-field field-events" required>
      <option value="">EVENTS TO REGISTER :</option>
      <option value="event1">Event 1</option>
      <option value="event2">Event 2</option>
      <option value="event3">Event 3</option>
    </select>

    <button type="submit" class="submit-button">REGISTER</button>
  </form>
</div>


<style>
.thank-you-wrapper {
  border-radius: 35px;
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  max-width: 431px;
  flex-direction: column;
  overflow: hidden;
  color: rgba(0, 0, 0, 1);
  font: 700 24px JetBrains Mono, sans-serif;
}

.content-container {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 657px;
  width: 100%;
  padding: 16px 12px 48px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.logo-image {
  aspect-ratio: 5.15;
  object-fit: contain;
  object-position: center;
  width: 402px;
}

.thank-you-message {
  position: relative;
  text-align: center;
  align-self: center;
  margin-top: 81px;
}

.contact-info {
  position: relative;
  align-self: start;
  margin: 43px 0 0 11px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="thank-you-wrapper">
  <div class="content-container">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/470078989f7740e3b5c959d0153ce29f/c1474b390cbabe8ea927dfb27a42b07d9731dd800c7d78062a5aaec4c1e38923?apiKey=470078989f7740e3b5c959d0153ce29f&"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/470078989f7740e3b5c959d0153ce29f/f32f2dd659426e80f2e0aabe4d570063762e5fbe096c26cb27cc03a9640d118f?apiKey=470078989f7740e3b5c959d0153ce29f&"
      class="logo-image"
      alt="Company Logo"
    />
    <div class="thank-you-message">
      THANK YOU
      <br />
      <br />
      "Join us for an exciting experience and make unforgettable
      memories—your participation will make this event truly special!"
    </div>
    <div class="contact-info">
      contact us
      <br />
      e-mail:sec@gmail.com
      <br />
      6854213598
      <br />
      6547895412
    </div>
  </div>
</div>
```
# OUTPUT:
![iPhone 14   15 Pro Max - 1](https://github.com/user-attachments/assets/0fe07822-3142-4aa4-9e09-dc746171aeba)
![Android Small - 1](https://github.com/user-attachments/assets/d3c34d35-3841-4235-a587-5cb5476578e2)
![Android Small - 2](https://github.com/user-attachments/assets/f64a22b4-0a2c-458b-b7e4-d468ac977bab)
![Figma basics](https://github.com/user-attachments/assets/bc4b905b-1568-4c82-8151-4fcbfafcd38a)


# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
