# SpectaCode
import React from 'react'
// import '../App.css';
import Navbar from './Navbar.css'
import logo from './images/logo.jpg'



function navbar() {
  return (
    <div>
    <div className="bg-dark p-4 stick">

      <ul className="nav justify-content-end">
     <div className="try"> <li className="nav-item">
      <span> <img src={logo}/></span>
    <a className="try"  href="#">SpectaCode</a>
          

        </li></div>
  <li className="nav-item">
    
    <a className=" right"  href="#">Home</a>
  </li>
  <li className="nav-item">
    <a className="right" href="#">About</a>
  </li>
  <li className="nav-item">
    <a className="right" href="#">Projects</a>
  </li>
  <li className="nav-item">
    <a className="right" href="#">Services</a>
  </li>
  <li className="nav-item">
    <a className="right" href="#">Contact Us</a>
  </li>
</ul> 
 
     
    </div>

    <div className="body">
      <h1>SpectaCode</h1>
      <h3>We love technology. </h3>
      <p>What we all share is our love for technology - in all its facets.</p>
    {/* <video width="100%" height="auto" autoplay muted playsinline >

<source src="soon.mp4" type="video/mp4"></source>
</video> */}
    </div>
    </div>
    
  
  )
}

export default navbar;
