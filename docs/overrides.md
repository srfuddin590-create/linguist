export default function Home() {
  return (
    <main style={{ padding: "40px", fontFamily: "Arial" }}>
      <h1 style={{ fontSize: "42px", fontWeight: "bold" }}>Littleland</h1>
      <p style={{ fontSize: "18px", marginTop: "10px", lineHeight: "1.6" }}>
        Welcome to Littleland — a simple, clean, and future-ready platform built for
        young learners and parents. Designed with clarity and trust, Littleland
        focuses on easy learning, creativity, and a safe digital space.
      </p>

      <h2 style={{ marginTop: "40px", fontSize: "28px" }}>Our Mission</h2>
      <p style={{ fontSize: "16px", lineHeight: "1.6" }}>
        Making education simple and enjoyable. Helping students grow with discipline,
        confidence, and creativity.
      </p>

      <h2 style={{ marginTop: "40px", fontSize: "28px" }}>Contact Us</h2>
      <p style={{ fontSize: "16px", lineHeight: "1.8" }}>
        Phone: <strong>8638895859</strong><br />
        Email: <strong>littleems@gmail.com</strong><br />
      </p>
    </main>   export default function Contact() {
  return (
    <main style={{ padding: "40px", fontFamily: "Arial" }}>
      <h1 style={{ fontSize: "36px", fontWeight: "bold" }}>Contact Littleland</h1>
      <p style={{ fontSize: "18px", marginTop: "10px", lineHeight: "1.6" }}>
        We’re here to answer questions, support parents, and guide young learners.
      </p>

      <h2 style={{ marginTop: "30px", fontSize: "24px" }}>Get in Touch</h2>
      <p style={{ fontSize: "16px", lineHeight: "1.8" }}>
        📞 Phone: <strong>8638895859</strong><br />
        📧 Email: <strong>littleems@gmail.com</strong>
      </p>
    </main>
  );
}
git add .
git commit -m "Updated homepage and added contact details"
git push
import Link from 'next/link';

export default function Navbar() {
  return (
    <nav style={{ 
      padding: "18px 30px", 
      display: "flex", 
      justifyContent: "space-between",
      backgroundColor: "#1a237e",
      color: "white",
      fontFamily: "Arial"
    }}>
      
      <div style={{ fontSize: "24px", fontWeight: "bold" }}>
        Littleland
      </div>

      <div style={{ display: "flex", gap: "25px", fontSize: "16px" }}>
        <Link href="/">Home</Link>
        <Link href="/about">About</Link>
        <Link href="/admission">Admission</Link>
        <Link href="/results">Results</Link>
        <Link href="/academics">Academics</Link>
        <Link href="/facilities">Facilities</Link>
        <Link href="/notices">Notices</Link>
        <Link href="/contact">Contact</Link>
      </div>
    </nav>
  );
}
import '../styles/globals.css';
import Navbar from '../components/Navbar';

export default function MyApp({ Component, pageProps }) {
  return (
    <>
      <Navbar />
      <Component {...pageProps} />
    </>
  );
}
export default function Admission() {
  return (
    <main style={{ padding: "40px", fontFamily: "Arial" }}>
      <h1 style={{ fontSize: "36px", fontWeight: "bold" }}>Admissions</h1>

      <p style={{ fontSize: "18px", marginTop: "20px", lineHeight: "1.8" }}>
        Littleland welcomes new students with a simple and transparent admission process.
      </p>

      <h2 style={{ marginTop: "30px", fontSize: "24px" }}>How to Apply</h2>
      <ul style={{ fontSize: "16px", lineHeight: "1.8" }}>
        <li>Fill the online admission form.</li>
        <li>Submit birth certificate and photo.</li>
        <li>Attend interaction/assessment session.</li>
        <li>Pay registration fees after selection.</li>
      </ul>

      <h2 style={{ marginTop: "30px", fontSize: "24px" }}>Contact</h2>
      <p>
        Phone: <strong>8638895859</strong><br />
        Email: <strong>littleems@gmail.com</strong>
      </p>
    </main>
  );
}
export default function Results() {
  return (
    <main style={{ padding: "40px", fontFamily: "Arial" }}>
      <h1 style={{ fontSize: "36px", fontWeight: "bold" }}>Results</h1>

      <p style={{ fontSize: "18px", marginTop: "20px", lineHeight: "1.8" }}>
        All academic results, entrance test results, and school performance updates will be posted here.
      </p>

      <h2 style={{ marginTop: "30px", fontSize: "24px" }}>Latest Results</h2>
      <ul style={{ fontSize: "16px", lineHeight: "1.8" }}>
        <li>No results uploaded yet.</li>
      </ul>
    </main>
  );
}
export default function Academics() {
  return (
    <main style={{ padding: "40px", fontFamily: "Arial" }}>
      <h1 style={{ fontSize: "36px", fontWeight: "bold" }}>Academics</h1>

      <p style={{ fontSize: "18px", marginTop: "20px", lineHeight: "1.8" }}>
        Littleland follows a balanced academic curriculum focusing on understanding,
        discipline, and curiosity. Subjects include English, Mathematics, Science,
        Social Science, Computer Studies, and Value Education.
      </p>
    </main>
  );
}
export default function Facilities() {
  return (
    <main style={{ padding: "40px", fontFamily: "Arial" }}>
      <h1 style={{ fontSize: "36px", fontWeight: "bold" }}>Facilities</h1>

      <p style={{ fontSize: "16px", marginTop: "15px", lineHeight: "1.8" }}>
        • Smart classrooms  
        • Library  
        • Safe campus  
        • Play area  
        • Activity-based learning  
      </p>
    </main>
  );
}

  );
}
