---
title: Elements
feature_text: |
  A demo of Markdown and HTML includes
feature_image: "https://picsum.photos/2560/600?image=873"
description: "A demo of Markdown and HTML includes"
sidebar: true
---
<style>
        .course-card {
            margin-bottom: 1.5rem;
        }
        .course-thumbnail img {
            width: 100%;
            height: auto;
        }
        .course-bookmark {
            position: absolute;
            top: 1rem;
            right: 1rem;
        }
        .course-meta {
            display: flex;
            justify-content: space-between;
        }
        .progress-circle {
            --size: 2.5rem;
            --pro: 0;
            width: var(--size);
            height: var(--size);
            border-radius: 50%;
            background: conic-gradient(#00d1b2 var(--pro), #f5f5f5 0 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.75rem;
            font-weight: bold;
        }
    </style>
  <section class="section">
        <div class="container">
            <div class="columns is-mobile is-multiline">
                <div class="column is-12">
                    <div class="is-flex is-justify-content-space-between">
                        <h1 class="title">Courses</h1>
                        <button class="button is-secondary">Filters</button>
                    </div>
                </div>
                <div class="column is-one-quarter">
                    <aside class="menu">
                        <p class="menu-label">Search</p>
                        <input class="input" type="text" placeholder="Search...">
                        <p class="menu-label">Category</p>
                        <ul class="menu-list">
                            <li><label><input type="checkbox"> Admin</label></li>
                            <li><label><input type="checkbox"> Business</label></li>
                            <li><label><input type="checkbox"> Design</label></li>
                            <li><label><input type="checkbox"> Development</label></li>
                        </ul>
                        <p class="menu-label">Tags</p>
                        <ul class="menu-list">
                            <li><label><input type="checkbox"> Admin</label></li>
                            <li><label><input type="checkbox"> Apex</label></li>
                            <li><label><input type="checkbox"> Basics</label></li>
                            <li><label><input type="checkbox"> Beginner</label></li>
                            <li><label><input type="checkbox"> Developer</label></li>
                            <li><label><input type="checkbox"> Fundamental</label></li>
                            <li><label><input type="checkbox"> Some Tags</label></li>
                        </ul>
                        <p class="menu-label">Level</p>
                        <ul class="menu-list">
                            <li><label><input type="checkbox"> All Levels</label></li>
                            <li><label><input type="checkbox"> Beginner</label></li>
                            <li><label><input type="checkbox"> Intermediate</label></li>
                            <li><label><input type="checkbox"> Expert</label></li>
                        </ul>
                        <p class="menu-label">Price</p>
                        <ul class="menu-list">
                            <li><label><input type="checkbox"> Free</label></li>
                            <li><label><input type="checkbox"> Paid</label></li>
                        </ul>
                        <button class="button is-small is-fullwidth">Clear All Filters</button>
                    </aside>
                </div>
                <div class="column is-three-quarters">
                    <div class="columns is-multiline">
                        <div class="column is-one-third course-card">
                            <div class="card">
                                <div class="card-image">
                                    <figure class="image is-4by3 course-thumbnail">
                                        <img src="https://namastesalesforce.com/wp-content/uploads/2024/05/what-is-salesforce.png" alt="Salesforce Fundamentals: Master the Basics">
                                    </figure>
                                    <span class="icon is-small course-bookmark">
                                        <i class="fas fa-bookmark"></i>
                                    </span>
                                </div>
                                <div class="card-content">
                                    <div class="media">
                                        <div class="media-content">
                                            <p class="title is-4">Salesforce Fundamentals: Master the Basics</p>
                                            <p class="subtitle is-6">By <a href="#">Admin</a></p>
                                        </div>
                                    </div>
                                    <div class="content">
                                        <p>Category: Admin</p>
                                        <div class="course-meta">
                                            <span><i class="fas fa-user"></i> 2</span>
                                            <span><i class="fas fa-clock"></i> 1h 30m</span>
                                        </div>
                                    </div>
                                    <button class="button is-primary is-fullwidth">Enroll Course</button>
                                </div>
                            </div>
                        </div>
                        <div class="column is-one-third course-card">
                            <div class="card">
                                <div class="card-image">
                                    <figure class="image is-4by3 course-thumbnail">
                                        <img src="https://namastesalesforce.com/wp-content/uploads/2024/04/Black-Yellow-Modern-Guide-YouTube-Thumbnail.png" alt="My First Course">
                                    </figure>
                                    <span class="icon is-small course-bookmark">
                                        <i class="fas fa-bookmark"></i>
                                    </span>
                                </div>
                                <div class="card-content">
                                    <div class="media">
                                        <div class="media-content">
                                            <p class="title is-4">My First Course</p>
                                            <p class="subtitle is-6">By <a href="#">Admin</a></p>
                                        </div>
                                    </div>
                                    <div class="content">
                                        <p>Categories: Business, Design</p>
                                        <div class="course-meta">
                                            <span><i class="fas fa-user"></i> 5</span>
                                            <span><i class="fas fa-clock"></i> 1h 27m</span>
                                        </div>
                                        <p class="has-text-weight-bold">Price: <del>₹21.00</del> ₹1.00</p>
                                        <div class="course-meta">
                                            <span class="progress-circle" style="--pro: 50;">50%</span>
                                            <span>50% Booked</span>
                                        </div>
                                    </div>
                                    <button class="button is-primary is-fullwidth">Add to cart</button>
                                </div>
                            </div>
                        </div>
                        <div class="column is-one-third course-card">
                            <div class="card">
                                <div class="card-image">
                                    <figure class="image is-4by3 course-thumbnail">
                                        <img src="https://namastesalesforce.com/wp-content/uploads/2024/05/Copy-of-Courses-2.png" alt="Apex Beginner: Learn Salesforce Programming Language">
                                    </figure>
                                    <span class="icon is-small course-bookmark">
                                        <i class="fas fa-bookmark"></i>
                                    </span>
                                </div>
                                <div class="card-content">
                                    <div class="media">
                                        <div class="media-content">
                                            <p class="title is-4">Apex Beginner: Learn Salesforce Programming Language</p>
                                            <p class="subtitle is-6">By <a href="#">Admin</a></p>
                                        </div>
                                    </div>
                                    <div class="content">
                                        <p>Category: Development</p>
                                        <div class="course-meta">
                                            <span><i class="fas fa-user"></i> 1</span>
                                            <span><i class="fas fa-clock"></i> 1h</span>
                                        </div>
                                    </div>
                                    <button class="button is-primary is-fullwidth">Enroll Course</button>
                                </div>
                            </div>
                        </div>
                        <!-- More course cards here -->
                    </div>
                </div>
            </div>
        </div>
    </section>
   