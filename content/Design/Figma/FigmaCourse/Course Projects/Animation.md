---
title: Animation
---

<!-- HTML Content -->
<div class="tweet-container">
    <div class="tweet-header">
        <img src="https://pbs.twimg.com/profile_images/1525644036157186055/mo5i70w-_400x400.png" alt="User Profile">
        <div class="user-info">
            <div class="user-details">
                <strong>Rajiv Mallisetty</strong>
                <span>@r_msetty · Follow</span>
            </div>
            <div class="user-icons">
                <a href="https://x.com/r_msetty/status/1869854377294606499" target="_blank">
                    <img src="https://assets1.chainstoreage.com/2023-07/twitter-x-logo.png" alt="X Icon">
                </a>
                <a href="https://www.linkedin.com/feed/update/urn:li:share:7280869133284458496/" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn Icon">
                </a>
                <a href="https://utdallas.startuptree.co/forum/2883/Figma-For-UI/UX-Business-%26-Startup-Uses---Day/Pt.-7" target="_blank">
                    <img src="https://2459647.fs1.hubspotusercontent-na1.net/hubfs/2459647/1accbb9b-015c-4678-83f8-7b3d6e978465.png" alt="StartupTree Icon">
                </a>
            </div>
        </div>
    </div>
    <div class="tweet-content">
Here is a feature I tried developing. It's an animation of a gradient, and it automatically shifts the order of the gradient in a smooth animation type feel. <br>
            <a href="https://www.figma.com/proto/l8F23L5Rp6nPrBq3p6vr9n/Untitled?t=eGy89bUV4vO4QCnN-1">https://www.figma.com/proto/l8F23L5Rp6nPrBq3p6vr9n/Untitled?t=eGy89bUV4vO4QCnN-1</a><br></br>
            
   Here a video to the demo:<br>
            <a href="https://www.loom.com/share/1e9945da5e644427866a7066c8714536?sid=57197e6a-ffb8-4eb3-a432-3a6b1552369e">https://www.loom.com/share/1e9945da5e644427866a7066c8714536?sid=57197e6a-ffb8-4eb3-a432-3a6b1552369e</a>
    </div>
    <div class="tweet-footer">
        <span>11:59 AM · Sep 4, 2024</span>
        <a href="#">26 Likes</a>
    </div>
</div>

</div>

<img src="./gradient.png" alt="Media Preview">

<hr>

<style>
    body {
        margin: 0;
        padding: 20px;
    }

    .tweet-container {
        max-width: 600px;
        margin: 20px auto;
        border: 1px solid #e1e8ed;
        border-radius: 10px;
        padding: 15px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .tweet-header {
        display: flex;
        align-items: center;
        margin-bottom: 10px;
    }

    .tweet-header img {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        margin-right: 10px;
    }
    .user-icons a img {
    width: 25px;
    height: 25px;
}

    .user-info {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
    }

    .user-details {
        font-size: 14px;
    }

    .user-details strong {
        display: block;
        font-weight: bold;
    }

    .user-details span {
        color: #657786;
    }

    .user-icons {
        display: flex;
        gap: 8px;
    }

    .user-icons img {
        width: 25px;
        height: 25px;
        cursor: pointer;
    }

    .user-icons img:hover {
        opacity: 0.8;
    }

    .tweet-content {
        font-size: 15px;
        margin-bottom: 10px;
    }

    .tweet-content a {
        color: #1da1f2;
        text-decoration: none;
    }

    .tweet-content a:hover {
        text-decoration: underline;
    }

    .tweet-footer {
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-size: 13px;
        color: #657786;
        margin-top: 10px;
    }

    .tweet-footer a {
        color: #657786;
        text-decoration: none;
    }

    .tweet-footer a:hover {
        text-decoration: underline;
    }

    /* New Style for Image */
    .tweet-content img {
        display: block;
        margin: 0 auto;
        width: 500px;
    }
        .reel-container {
        max-width: 600px;
        margin: 20px auto;
        border: 1px solid #e1e8ed;
        border-radius: 10px;
        padding: 15px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .reel-header {
        display: flex;
        align-items: center;
        margin-bottom: 10px;
    }

    .reel-header img {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        margin-right: 10px;
    }

    .reel-info {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
    }

    .user-details {
        font-size: 14px;
    }

    .user-details strong {
        display: block;
        font-weight: bold;
    }

    .user-details span {
        color: #657786;
    }

    .reel-content iframe {
        width: 100%;
        height: 500px;
        border: none;
        margin-bottom: 10px;
    }

    .reel-footer {
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-size: 13px;
        color: #657786;
        margin-top: 10px;
    }

    .reel-footer a {
        color: #657786;
        text-decoration: none;
    }

    .reel-footer a:hover {
        text-decoration: underline;
    }
</style>