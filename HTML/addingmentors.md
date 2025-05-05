# How to Add a New Mentor to the Filtered Directory

This guide explains how to manually add a new mentor to the "Find a Mentor" page using the existing filter system in Elementor (free version). All mentors are stored inside a single HTML widget.

---

## 1. Open the Mentor Page in Elementor

- Go to the WordPress dashboard.
- Navigate to **Pages** > **Find a Mentor (All)**.
- Click **Edit with Elementor**.

---

## 2. Locate the HTML Widget

- Scroll down the page until you find the section displaying all mentors.
- Click on the **HTML widget** that contains the filter code and mentor cards.
- Open it to edit the HTML content.

---

## 3. Copy an Existing Mentor Card

Find one of the existing mentor cards. It will look like this:

```html
<div class="mentor-card" data-featured="yes" data-type="tech" data-gender="female">
  <img src="https://via.placeholder.com/150" alt="Mentor Photo" />
  <h3>Aaliyah Khan</h3>
  <p>Tech Degree Apprentice</p>
  <p>Fun Fact – I build websites for fun</p>
  <a href="#">Book Now</a>
</div>
```
4. Update the New Mentor’s Info
Change the following values:
| Attribute/Tag     | What to Replace With                           |
| ----------------- | ---------------------------------------------- |
| `data-featured`   | `"yes"` for featured mentors, `"no"` otherwise |
| `data-type`       | `"tech"`, `"finance"`, `"project"`, etc.       |
| `data-gender`     | `"male"` or `"female"`                         |
| `<img src="...">` | Replace with the mentor’s actual image URL     |
| `<h3>...</h3>`    | Mentor's name                                  |
| `<p>...</p>`      | Job title and fun fact                         |
| `<a href="#">`    | Link to their BookingPress form                |

Example:
<div class="mentor-card" data-featured="no" data-type="finance" data-gender="male">
  <img src="https://yourwebsite.com/images/james.png" alt="Mentor Photo" />
  <h3>James Ali</h3>
  <p>Finance Degree Apprentice</p>
  <p>Fun Fact – I love budgeting spreadsheets</p>
  <a href="https://bookingpresslink.com/james">Book Now</a>
</div>

5. Save and Preview
Click Update in Elementor after adding the new mentor.

Preview the page to confirm the new card appears correctly.

Use the filters (Gender, Apprenticeship Type, Featured) to check that the mentor shows/hides correctly.

6. Optional: Add Labels for Clarity
To keep things organised, you can label each mentor in the code with an HTML comment:

<!-- MENTOR: James Ali -->
<div class="mentor-card" ...>
  ...
</div>


This helps when editing a long list of mentors later.

Summary
All mentors live inside one HTML widget.

You copy and paste card blocks manually.

Filters work based on the data-featured, data-type, and data-gender attributes.

No plugins or Elementor Pro required.
