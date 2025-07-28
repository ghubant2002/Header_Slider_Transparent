# Header_Slider_Transparent
Customized Header &amp; Slider Banner Section(Transparent)


/*------------- GRID SYSTEM (Normal Mode) -------------- */

.gides
{
    display: grid;
    gap: 1.5rem;
    margin-top: 3rem;
    grid-template-columns: repeat(auto-fit, minmax(min(270px, 8rem), 1fr));
}

.wb-grid (for image)
{
    overflow: hidden;
    border-radius:14px;
    position: relative;
}

.wb-grid (for text)
{
    text-align: center;
    padding:30px;
}


/*------------- GRID SYSTEM (Responsive Mode for tab & phone) -------------- */

.gides
{
    gap: 1.8rem;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
}

.wb-grid (for text)
{
    text-align: center;
    padding:15px;
}


/*------------- Form -------------- */

<div class="mb-3">
  <input class="form-control al-form-font" type="text" name="name" placeholder="Your Name" required>
</div>
<div class="mb-3">
  <input class="form-control al-form-font" type="email" name="email" placeholder="E-mail Address" required>
</div>
<div class="mb-3">
  <input class="form-control al-form-font" type="email" name="phonenumber" placeholder="Phone No" required>
</div>
<div class="mb-3">
  <select class="form-select al-form-font mt-3" required>
    <option selected value="">Select Service</option>
    <option value="">Junior Web Developer</option>
    <option value="">Senior Web Developer</option>
    <option value="">Project Manager</option>
  </select>
</div>


/*------------- Media Query -------------- */

/*---------Responsive Design for Desktop----------------*/

@media screen and (max-width:1140px) and (min-width:992px)


/*---------Responsive Design for Tab----------------*/

@media screen and (max-width:991px) and (min-width:768px)


/*---------Responsive Design for Smartphone----------------*/

@media screen and (max-width:767px) and (min-width:576px)


@media screen and (max-width:575px) and (min-width:360px)



/*------------- LINKS (Head Section) -------------- */

<!-- Bootstrap CSS File Link -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Font Awesome File Css Link -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" />

<!-- Font Awesome File js link -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/js/all.min.js" ></script>

<!-- AOS animation -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" integrity="sha512-1cK78a1o+ht2JcaW6g8OXYwqpev9+6GqOkz9xmBN9iUUhIndKtxwILGWYOSibOKjLsEdjyjZvYDq/cZwNeak0w==" crossorigin="anonymous" referrerpolicy="no-referrer" />


/*------------- LINKS (Body Section) -------------- */

<!-- JQuery Link -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>

<!-- Bootstrap JS File Link -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

<!-- AOS animation -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js" integrity="sha512-A7AYk1fGKX6S2SsHywmPkrnzTZHrgiVT7GcQkLGDe2ev0aWb8zejytzS8wjo7PGEXKqJOrjQ4oORtnimIRZBtw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
<script>
  AOS.init();
</script>

