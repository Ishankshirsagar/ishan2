/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #fafafa;
}

/* Navbar */
.navbar {
  background-color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
  border-bottom: 1px solid #ddd;
}

.logo {
  font-size: 24px;
  font-weight: bold;
}

.search {
  padding: 5px;
  border: 1px solid #ccc;
  border-radius: 3px;
}

.nav-links a {
  margin: 0 10px;
  text-decoration: none;
  color: #333;
}

/* Profile Section */
.profile {
  display: flex;
  align-items: center;
  padding: 20px;
  background-color: #fff;
  border-bottom: 1px solid #ddd;
}

.profile-pic {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin-right: 20px;
}

.profile-info h2 {
  font-size: 24px;
}

.profile-info p {
  color: #555;
}

/* Feed Section */
.feed {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
  padding: 20px;
}

.feed-item img {
  width: 100%;
  height: auto;
  border-radius: 5px;
}
