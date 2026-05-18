# Bug List

## 1. Project not started yet
**Status:** Resolved  

---

## 2. Multiple typos across the site
**Status:** Ongoing  

---

## 3. Header image not displaying correctly
**Cause:** Image scaling and sizing issues with the banner  
**Status:** Partially resolved  

---

## 4. Navigation menu not horizontal
**Cause:** Missing `nav ul` selector in CSS  
**Status:** Resolved  

---

## 5. “Back to Home” and “Submit” buttons are too close together
**Status:** Not fixed  

---

## 6. Missing participant page for sign-up form
**Note:** Realized this was needed after the initial design phase  
**Status:** Resolved  

---

## 7. JavaScript for sign-up form not working
**Cause:** Local testing issues and script placement problems  
**Status:** Resolved  

---

## 8. Sign-up data only stored locally (no persistence)
**Cause:** Using `localStorage` instead of a backend or form service  
**Status:** Identified / Planned fix with Netlify Forms  

---

## 9. Navigation menu does not scale properly on smaller screens
**Cause:** Fixed width navigation buttons and lack of responsive layout adjustments  
**Status:** Ongoing  

---

## 10. Navigation links not working correctly between English and Swedish pages
**Cause:** Links only used `#section-id` instead of linking to the correct page first  
**Status:** Resolved  

---

## 11. Fixed bottom navigation overlapping page content
**Cause:** Fixed navigation bar covered sections when scrolling  
**Fix:** Added `scroll-padding-bottom` in CSS  
**Status:** Resolved  

---

## 12. Text readability issues due to long paragraphs
**Cause:** Text width too large and paragraphs too dense  
**Status:** Improved  

---

## 13. Website lacked language switch between Swedish and English
**Cause:** No navigation between translated pages  
**Status:** Resolved  

---

# Images / References

- ![Bug 7 – JS signup not adding to participants](bug_nr_7.png)

- ![Bug 9 – Menu not scaling correctly](bug_nr_9.png)