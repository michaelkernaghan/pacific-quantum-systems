# Pacific Quantum Systems - Full Site Review Bundle


============================================================
# index.html
============================================================

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pacific Quantum Systems</title>
  <meta name="description" content="Research at the intersection of quantum foundations, post-quantum cryptography, and quantum communications.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

<nav>
  <div class="nav-inner">
    <a href="index.html" class="logo">Pacific <span>Quantum</span> Systems</a>
    <button class="menu-toggle" onclick="document.querySelector('nav ul').classList.toggle('open')">&#9776;</button>
    <ul>
      <li><a href="index.html" class="active">Home</a></li>
      <li><a href="research.html">Research</a></li>
      <li><a href="computational.html">Computation</a></li>
      <li><a href="pqc.html">Post-Quantum Crypto</a></li>
      <li><a href="quantum-comms.html">Quantum Comms</a></li>
      <li><a href="about.html">About</a></li>
    </ul>
  </div>
</nav>

<section class="hero">
  <h1>Quantum foundations.<br><span class="highlight">Applied forward.</span></h1>
  <p class="subtitle">
    Pacific Quantum Systems is a research initiative exploring the mathematical
    structures underlying quantum mechanics and their implications for
    cryptography and secure communications.
  </p>
</section>

<div class="content">
  <div class="cards">

    <a href="research.html" class="pillar-link">
      <div class="card">
        <span class="icon">&#9670;</span>
        <span class="badge">Foundations</span>
        <h3>Quantum Contextuality</h3>
        <p>
          Algebraic classification of Kochen-Specker sets in dimension three.
          The norm-2 boundary, six constructions from algebraic rings, and
          connections to perfect quantum strategies.
        </p>
      </div>
    </a>

    <a href="pqc.html" class="pillar-link">
      <div class="card">
        <span class="icon">&#9919;</span>
        <span class="badge">Cryptography</span>
        <h3>Post-Quantum Cryptography</h3>
        <p>
          Tracking the transition to quantum-resistant algorithms. Lattice-based
          cryptography, NIST standards (ML-DSA, ML-KEM, SLH-DSA), and
          blockchain integration with Tezos tz5 addresses.
        </p>
      </div>
    </a>

    <a href="quantum-comms.html" class="pillar-link">
      <div class="card">
        <span class="icon">&#8644;</span>
        <span class="badge">Communications</span>
        <h3>Quantum Networks</h3>
        <p>
          Quantum key distribution protocols, the Canadian quantum
          communications landscape, and the classical-quantum software interface
          enabling secure network infrastructure.
        </p>
      </div>
    </a>

  </div>

  <h2>Why This Matters</h2>
  <p>
    Quantum computing threatens the cryptographic foundations of modern digital
    infrastructure. The question is not <em>whether</em> current encryption will
    be broken, but <em>when</em> &mdash; and whether we will have deployed
    quantum-resistant alternatives in time.
  </p>
  <p>
    Our work connects three levels: the fundamental mathematics of quantum
    mechanics (contextuality), the algebraic structures that make quantum-safe
    cryptography possible (lattice problems), and the physical layer that
    enables provably secure communication (quantum key distribution).
  </p>

  <div class="callout">
    <p>
      <strong>Current focus:</strong> A computational classification of
      Kochen-Specker constructions from algebraic rings, revealing that
      generator norm &le; 2 controls KS-uncolorability in dimension three
      &mdash; with implications for quantum advantage in nonlocal games.
    </p>
  </div>
</div>

<footer>
  <p>&copy; 2026 Pacific Quantum Systems &middot; Vancouver, BC</p>
</footer>

</body>
</html>



============================================================
# research.html
============================================================

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Research — Pacific Quantum Systems</title>
  <meta name="description" content="Quantum contextuality research: algebraic classification of Kochen-Specker sets, the norm-2 boundary, and connections to quantum advantage.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

<nav>
  <div class="nav-inner">
    <a href="index.html" class="logo">Pacific <span>Quantum</span> Systems</a>
    <button class="menu-toggle" onclick="document.querySelector('nav ul').classList.toggle('open')">&#9776;</button>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="research.html" class="active">Research</a></li>
      <li><a href="computational.html">Computation</a></li>
      <li><a href="pqc.html">Post-Quantum Crypto</a></li>
      <li><a href="quantum-comms.html">Quantum Comms</a></li>
      <li><a href="about.html">About</a></li>
    </ul>
  </div>
</nav>

<div class="page-header">
  <h1>Quantum Contextuality Research</h1>
  <p>Algebraic structures underlying quantum mechanics and the Kochen-Specker theorem</p>
</div>

<div class="content">

  <h2>The Algebraic Landscape of Kochen-Specker Sets</h2>
  <p>
    The Kochen-Specker (KS) theorem is one of the foundational results in quantum
    mechanics. It proves that quantum measurement outcomes cannot be predetermined
    independently of which other compatible measurements are performed &mdash; a
    property called <em>contextuality</em>.
  </p>
  <p>
    Our research asks a new question: <strong>what algebraic invariant controls
    whether a set of quantum measurements exhibits contextuality?</strong>
  </p>

  <div class="callout">
    <p>
      <strong>Central thesis:</strong> Generator norm &le; 2 is the controlling
      invariant for KS-uncolorability in dimension three. The integer identity
      1+1=2, the Peres identity (&radic;2)&sup2;=2, and the Eisenstein identity
      1+&omega;+&omega;&sup2;=0 are all manifestations of the same algebraic
      constraint.
    </p>
  </div>

  <h2>Six Constructions from Algebraic Rings</h2>
  <p>
    A systematic computational survey across algebraic number fields reveals that
    KS-uncolorable sets in dimension three arise from exactly six algebraic rings
    &mdash; discrete constructions separated by algebraic structure rather than
    continuous parameters.
  </p>

  <table>
    <thead>
      <tr>
        <th>Construction</th>
        <th>Ring</th>
        <th>Min KS Size</th>
        <th>Cancellation Identity</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Integer (Conway-Kochen)</td>
        <td><code>&Zopf;</code></td>
        <td>31</td>
        <td>1 + 1 = 2</td>
      </tr>
      <tr>
        <td>Peres</td>
        <td><code>&Zopf;[&radic;2]</code></td>
        <td>33</td>
        <td>(&radic;2)&sup2; = 2</td>
      </tr>
      <tr>
        <td>Eisenstein</td>
        <td><code>&Zopf;[&omega;]</code></td>
        <td>33</td>
        <td>1 + &omega; + &omega;&sup2; = 0</td>
      </tr>
      <tr>
        <td>&Zopf;[&radic;-2]</td>
        <td><code>&Zopf;[&radic;-2]</code></td>
        <td>33</td>
        <td>|&radic;-2|&sup2; = 2</td>
      </tr>
      <tr>
        <td>Heegner-7</td>
        <td><code>&Zopf;[(1+&radic;-7)/2]</code></td>
        <td>43</td>
        <td>&alpha;&middot;&alpha;&#x0305; = 2</td>
      </tr>
      <tr>
        <td>Golden</td>
        <td><code>&Zopf;[&phi;]</code></td>
        <td>52</td>
        <td>&phi;&sup2; = &phi; + 1</td>
      </tr>
    </tbody>
  </table>

  <p>
    The Heegner-7 and Golden constructions are newly discovered &mdash; they do not
    appear in any existing KS catalogue. The Golden construction is particularly
    remarkable: invisible to direct alphabet search, it emerges only through
    cross-product completion of the coordinate set.
  </p>

  <h2>Graph Universality</h2>
  <p>
    A striking structural result: all known 31-vertex KS sets &mdash; whether constructed
    from integer coordinates, rational fields, mixed-field alphabets, or group-theoretic
    orbits (A<sub>4</sub>, S<sub>4</sub>) &mdash; are graph-isomorphic. The
    orthogonality graph appears to be a universal invariant at the minimum size.
  </p>

  <h2>Connection to Quantum Advantage</h2>
  <p>
    Every KS set defines a <em>bipartite perfect quantum strategy</em> (BPQS) &mdash;
    a nonlocal game where quantum players achieve perfect coordination that is
    impossible classically. The algebraic structure of the KS set directly determines
    the size and efficiency of the resulting quantum advantage.
  </p>

  <table>
    <thead>
      <tr>
        <th>Construction</th>
        <th>|S<sub>A</sub>| &times; |S<sub>B</sub>|</th>
        <th>Product</th>
        <th>Status</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>Eisenstein-33</td><td>5 &times; 9</td><td>45</td><td>Exact</td></tr>
      <tr><td>Peres-33</td><td>7 &times; 9</td><td>63</td><td>Exact</td></tr>
      <tr><td>Conway-Kochen-31</td><td>8 &times; 9</td><td>&le;72</td><td>Best found</td></tr>
      <tr><td>&Zopf;[&radic;-2]-33</td><td>7 &times; 9</td><td>63</td><td>Exact (new)</td></tr>
      <tr><td>Heegner-7-43</td><td>9 &times; 12</td><td>&le;108</td><td>Best found (new)</td></tr>
      <tr><td>Golden-52</td><td>12 &times; 13</td><td>&le;156</td><td>Best found (new)</td></tr>
    </tbody>
  </table>

  <h2>Key Results</h2>
  <ul>
    <li><strong>6|n Conjecture:</strong> n-th roots of unity produce KS-uncolorable sets if and only if 6 divides n (verified for n &le; 30)</li>
    <li><strong>Realizability gap:</strong> 49% of random abstract hypergraphs are KS-uncolorable, but 0% are realizable in &Ropf;&sup3; &mdash; geometric embedding is the true bottleneck</li>
    <li><strong>Fragility:</strong> The Conway-Kochen 31-vector set is destroyed by 1% coordinate perturbation, confirming the discrete algebraic nature of KS contextuality</li>
    <li><strong>Norm-2 boundary:</strong> At generator norm &ge; 3, the cancellation identities required for orthogonality become impossible</li>
  </ul>

  <h2>Historical Context</h2>
  <p>
    The study of finite KS sets has a rich history stretching from the original
    Kochen-Specker theorem (1967) through the Peres 33-vector construction (1991),
    the Kernaghan 20-vector set in four dimensions (1994), the Kernaghan-Peres
    40-vector construction connecting to GHZ paradoxes (1995), and the Cabello
    18-vector minimal set in four dimensions (1996). Our work extends this tradition
    into the algebraic domain, classifying for the first time which number fields
    support contextuality in the smallest nontrivial dimension.
  </p>

  <h2>Publications</h2>
  <ul>
    <li>
      M. Kernaghan, &ldquo;The Algebraic Landscape of Kochen-Specker Sets in
      Dimension Three&rdquo; (2026). <em>In preparation for Physical Review A.</em>
    </li>
    <li>
      M. Kernaghan, &ldquo;New KS Sets from Algebraic Number Fields with Enhanced
      Contextual Advantage&rdquo; (2026). <em>In preparation for Physical Review Letters.</em>
    </li>
    <li>
      M. Kernaghan, &ldquo;Graph Universality of CK-31 and the Norm-2 Boundary&rdquo;
      (2026). <em>In preparation for Physical Review Letters.</em>
    </li>
  </ul>

  <h3>Earlier Publications</h3>
  <ul>
    <li>M. Kernaghan, &ldquo;Bell-Kochen-Specker theorem for 20 vectors,&rdquo; <em>J. Phys. A</em> <strong>27</strong>, L829 (1994).</li>
    <li>M. Kernaghan and A. Peres, &ldquo;Kochen-Specker theorem for eight-dimensional space,&rdquo; <em>Phys. Lett. A</em> <strong>198</strong>, 1&ndash;5 (1995).</li>
  </ul>

</div>

<footer>
  <p>&copy; 2026 Pacific Quantum Systems &middot; Vancouver, BC</p>
</footer>

</body>
</html>



============================================================
# computational.html
============================================================

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Computational Quantum Foundations — Pacific Quantum Systems</title>
  <meta name="description" content="Using computational methods — SAT solvers, graph algorithms, and algebraic search — to discover new results in quantum foundations.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

<nav>
  <div class="nav-inner">
    <a href="index.html" class="logo">Pacific <span>Quantum</span> Systems</a>
    <button class="menu-toggle" onclick="document.querySelector('nav ul').classList.toggle('open')">&#9776;</button>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="research.html">Research</a></li>
      <li><a href="computational.html" class="active">Computation</a></li>
      <li><a href="pqc.html">Post-Quantum Crypto</a></li>
      <li><a href="quantum-comms.html">Quantum Comms</a></li>
      <li><a href="about.html">About</a></li>
    </ul>
  </div>
</nav>

<div class="page-header">
  <h1>Computational Quantum Foundations</h1>
  <p>Computers as instruments for foundational discovery in quantum mechanics</p>
</div>

<div class="content">

  <h2>A New Kind of Instrument</h2>
  <p>
    Foundational quantum mechanics has traditionally been the domain of pen-and-paper
    proof: thought experiments, algebraic manipulations, and elegant constructions by
    hand. But many of the deepest questions in quantum foundations are fundamentally
    combinatorial &mdash; they concern the existence or non-existence of structures
    satisfying specific constraints across vast search spaces.
  </p>
  <p>
    The computer is not replacing mathematical reasoning. It is extending it into
    territory that is inaccessible to human intuition alone. Just as the telescope
    revealed structure invisible to the naked eye, computational search reveals
    mathematical structure that no amount of clever manipulation could have uncovered.
  </p>

  <div class="callout">
    <p>
      The discovery that the golden ratio field <code>&Zopf;[&phi;]</code> supports
      Kochen-Specker sets was invisible to direct algebraic search. It emerged only
      when a computer systematically applied cross-product closure to coordinate
      sets &mdash; a process that generates hundreds of candidate vectors and tests
      billions of combinations.
    </p>
  </div>

  <h2>The Computational Toolkit</h2>
  <p>
    Our research draws on several families of algorithms, each suited to a different
    aspect of the problem.
  </p>

  <h3>SAT Solvers for Uncolorability</h3>
  <p>
    The central question &mdash; can a set of quantum measurements be assigned
    predetermined outcomes consistently? &mdash; is a constraint satisfaction
    problem. We encode it as a Boolean satisfiability (SAT) instance:
  </p>
  <ul>
    <li>Each vector gets a Boolean variable (included in the KS set or not)</li>
    <li>Orthogonality constraints become clauses (exactly one vector per basis must be &ldquo;true&rdquo;)</li>
    <li>KS-uncolorability means the formula is <strong>unsatisfiable</strong> &mdash; no consistent assignment exists</li>
  </ul>
  <p>
    Modern CDCL solvers (we use Glucose4 via PySAT) can resolve these instances
    in milliseconds for sets of 30&ndash;60 vectors, and provide <em>proofs</em>
    of unsatisfiability &mdash; not just answers, but certificates that can be
    independently verified.
  </p>

  <h3>Graph Algorithms</h3>
  <p>
    The orthogonality structure of a KS set defines a graph (vectors are vertices,
    orthogonal pairs are edges) and a hypergraph (bases are hyperedges). These
    structures encode the combinatorial skeleton of contextuality.
  </p>
  <ul>
    <li><strong>Graph isomorphism (VF2):</strong> Testing whether KS sets from different algebraic rings share the same combinatorial structure</li>
    <li><strong>Spectral analysis:</strong> Eigenvalues of the adjacency matrix reveal symmetry and regularity</li>
    <li><strong>Lov&aacute;sz theta:</strong> A semidefinite programming bound that connects graph structure to quantum advantage &mdash; the ratio &theta;/&alpha; quantifies the contextual advantage</li>
    <li><strong>Fractional chromatic number:</strong> Another graph invariant linked to the quantum-classical gap</li>
  </ul>

  <h3>Algebraic Search</h3>
  <p>
    Enumerating KS candidates requires generating vectors from algebraic number
    fields and testing orthogonality. The search space grows combinatorially:
  </p>
  <ul>
    <li><strong>Alphabet generation:</strong> For a ring like <code>&Zopf;[&radic;2]</code>, enumerate all vectors with coordinates of bounded norm</li>
    <li><strong>Cross-product closure:</strong> Given a seed set, compute all cross products to discover vectors not in the original alphabet</li>
    <li><strong>Greedy minimization:</strong> Starting from a large uncolorable pool, iteratively remove vectors while preserving uncolorability</li>
    <li><strong>Exhaustive minimization:</strong> SAT-based approach that provably finds minimal KS subsets</li>
  </ul>

  <h3>Integer and Linear Programming</h3>
  <p>
    Bipartite perfect quantum strategies (BPQS) require finding optimal partitions
    of KS bases into two sets satisfying coverage constraints. We use integer
    linear programming to find exact solutions when they exist, and bound the
    optimum otherwise.
  </p>

  <h2>What Computation Has Revealed</h2>
  <p>
    Several of our key results would have been difficult or impossible to obtain
    without computational methods:
  </p>

  <table>
    <thead>
      <tr>
        <th>Discovery</th>
        <th>Method</th>
        <th>Why Computation Was Essential</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Golden ratio KS set</td>
        <td>Cross-product closure + SAT</td>
        <td>Invisible to direct alphabet search; requires generating ~200 vectors and testing all subsets</td>
      </tr>
      <tr>
        <td>Heegner-7 KS set</td>
        <td>Algebraic search + SAT</td>
        <td>Ring <code>&Zopf;[(1+&radic;-7)/2]</code> not previously considered; found by systematic survey across number fields</td>
      </tr>
      <tr>
        <td>Graph universality of CK-31</td>
        <td>VF2 isomorphism</td>
        <td>Comparing graph structure across algebraically unrelated constructions requires exhaustive pairwise testing</td>
      </tr>
      <tr>
        <td>6|n conjecture</td>
        <td>Roots-of-unity survey</td>
        <td>Testing all n-th roots of unity for n &le; 30 generates thousands of candidate sets</td>
      </tr>
      <tr>
        <td>Realizability gap (49% vs 0%)</td>
        <td>Random hypergraph generation + geometric embedding</td>
        <td>Statistical claim requires sampling thousands of random structures</td>
      </tr>
      <tr>
        <td>Norm-2 boundary</td>
        <td>Systematic field survey</td>
        <td>Negative results (no KS sets at norm &ge; 3) require exhaustive search to be convincing</td>
      </tr>
    </tbody>
  </table>

  <h2>Reproducibility</h2>
  <p>
    Computational results in foundational physics must meet a high standard of
    reproducibility. Our approach:
  </p>
  <ul>
    <li><strong>Fixed random seeds:</strong> All stochastic processes use <code>random.seed(42)</code> for exact reproducibility</li>
    <li><strong>Multiple verification paths:</strong> Key results confirmed by at least two independent algorithms (e.g., SAT + direct enumeration)</li>
    <li><strong>Certificate-based proofs:</strong> SAT unsatisfiability provides machine-checkable certificates</li>
    <li><strong>Open methodology:</strong> Complete algorithmic descriptions in publications, enabling independent replication</li>
  </ul>

  <h2>The Role of AI</h2>
  <p>
    Large language models are emerging as a new tool in computational research &mdash;
    not for proof, but for <em>exploration</em>. In this work, AI assisted with:
  </p>
  <ul>
    <li><strong>Literature synthesis:</strong> Connecting results across quantum foundations, graph theory, and algebraic number theory</li>
    <li><strong>Code generation and debugging:</strong> Rapidly prototyping search algorithms and visualization tools</li>
    <li><strong>Hypothesis generation:</strong> Suggesting algebraic structures to investigate based on pattern recognition</li>
    <li><strong>Peer review simulation:</strong> Identifying weaknesses in arguments before formal submission</li>
  </ul>
  <p>
    The key discipline is that AI suggestions are always verified computationally
    or mathematically. The computer proposes; the mathematics disposes.
  </p>

  <div class="callout">
    <p>
      <strong>The computer as collaborator:</strong> The best results in computational
      quantum foundations come from a tight loop between human mathematical intuition
      (&ldquo;what structure might exist here?&rdquo;) and computational power
      (&ldquo;let me check every possibility&rdquo;). Neither alone would have
      found the golden ratio construction. Together, they did.
    </p>
  </div>

  <h2>Software Stack</h2>
  <table>
    <thead>
      <tr>
        <th>Tool</th>
        <th>Role</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>Python 3.11</td><td>Primary language for all computational work</td></tr>
      <tr><td>PySAT (Glucose4)</td><td>SAT solving for uncolorability and minimization</td></tr>
      <tr><td>NumPy / SciPy</td><td>Linear algebra, eigenvalue computation, optimization</td></tr>
      <tr><td>CVXPY (SCS solver)</td><td>Semidefinite programming for Lov&aacute;sz theta</td></tr>
      <tr><td>NetworkX</td><td>Graph construction, isomorphism (VF2), spectral analysis</td></tr>
      <tr><td>pdflatex (MiKTeX)</td><td>Paper compilation</td></tr>
    </tbody>
  </table>

</div>

<footer>
  <p>&copy; 2026 Pacific Quantum Systems &middot; Vancouver, BC</p>
</footer>

</body>
</html>



============================================================
# pqc.html
============================================================

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Post-Quantum Cryptography — Pacific Quantum Systems</title>
  <meta name="description" content="Post-quantum cryptography: lattice-based algorithms, NIST standards, and blockchain integration for quantum-resistant infrastructure.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

<nav>
  <div class="nav-inner">
    <a href="index.html" class="logo">Pacific <span>Quantum</span> Systems</a>
    <button class="menu-toggle" onclick="document.querySelector('nav ul').classList.toggle('open')">&#9776;</button>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="research.html">Research</a></li>
      <li><a href="computational.html">Computation</a></li>
      <li><a href="pqc.html" class="active">Post-Quantum Crypto</a></li>
      <li><a href="quantum-comms.html">Quantum Comms</a></li>
      <li><a href="about.html">About</a></li>
    </ul>
  </div>
</nav>

<div class="page-header">
  <h1>Post-Quantum Cryptography</h1>
  <p>Preparing cryptographic infrastructure for the quantum era</p>
</div>

<div class="content">

  <h2>The Quantum Threat</h2>
  <p>
    Shor's algorithm, running on a sufficiently large quantum computer, can factor
    integers and compute discrete logarithms in polynomial time. This breaks RSA,
    ECDSA, and every widely-deployed public-key cryptosystem. Grover's algorithm
    provides a quadratic speedup for brute-force search, effectively halving
    symmetric key lengths.
  </p>
  <p>
    The timeline is uncertain, but the threat is not: &ldquo;harvest now, decrypt
    later&rdquo; attacks mean that data encrypted today with vulnerable algorithms
    may already be at risk.
  </p>

  <h2>NIST Post-Quantum Standards</h2>
  <p>
    In 2024, NIST finalized three post-quantum cryptographic standards after an
    eight-year evaluation process. These algorithms are built on mathematical
    problems believed to be hard for both classical and quantum computers.
  </p>

  <table>
    <thead>
      <tr>
        <th>Standard</th>
        <th>Algorithm</th>
        <th>Type</th>
        <th>Hard Problem</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>FIPS 204</code></td>
        <td>ML-DSA (Dilithium)</td>
        <td>Digital Signature</td>
        <td>Module-LWE</td>
      </tr>
      <tr>
        <td><code>FIPS 203</code></td>
        <td>ML-KEM (Kyber)</td>
        <td>Key Encapsulation</td>
        <td>Module-LWE</td>
      </tr>
      <tr>
        <td><code>FIPS 205</code></td>
        <td>SLH-DSA (SPHINCS+)</td>
        <td>Digital Signature</td>
        <td>Hash functions</td>
      </tr>
    </tbody>
  </table>

  <h2>Lattice-Based Cryptography</h2>
  <p>
    The dominant approach to post-quantum cryptography is built on lattice problems.
    A <em>lattice</em> is a regular grid of points in high-dimensional space. Two
    problems form the security foundation:
  </p>
  <ul>
    <li>
      <strong>Learning With Errors (LWE):</strong> Given a system of approximate
      linear equations over a finite field, recover the secret vector. The &ldquo;errors&rdquo;
      (small noise terms) make this problem exponentially hard in the lattice dimension.
    </li>
    <li>
      <strong>Shortest Vector Problem (SVP):</strong> Find the shortest nonzero
      vector in a lattice. No known quantum algorithm provides better than marginal
      improvement over classical approaches.
    </li>
  </ul>

  <div class="callout">
    <p>
      ML-DSA-44 (the smallest parameter set) produces signatures of 2,420 bytes
      with public keys of 1,312 bytes &mdash; significantly larger than ECDSA's
      64-byte signatures and 33-byte keys. This size increase is the primary
      engineering challenge for adoption.
    </p>
  </div>

  <h2>Blockchain Integration: Tezos tz5 Addresses</h2>
  <p>
    Blockchain systems face an acute PQC challenge: addresses are derived directly
    from public keys, and transactions are authenticated by digital signatures.
    Every on-chain asset is ultimately protected by the signature scheme.
  </p>
  <p>
    Tezos is actively developing <strong>tz5 addresses</strong> based on ML-DSA
    (Dilithium) for quantum-resistant account security. Key developments:
  </p>
  <ul>
    <li>New <code>tz5</code> address prefix for ML-DSA-44 public keys</li>
    <li>Larger transaction sizes due to PQC signature overhead</li>
    <li>Initial restrictions: tz5 accounts may have limited smart contract interaction</li>
    <li>Protocol-level changes required for consensus participation</li>
  </ul>
  <p>
    We track tz5 development through the Tezos GitLab, monitoring merge requests,
    protocol proposals, and test network deployments.
  </p>

  <h2>Current Address Types in Tezos</h2>
  <table>
    <thead>
      <tr>
        <th>Prefix</th>
        <th>Curve / Algorithm</th>
        <th>Status</th>
      </tr>
    </thead>
    <tbody>
      <tr><td><code>tz1</code></td><td>Ed25519</td><td>Active (most common)</td></tr>
      <tr><td><code>tz2</code></td><td>secp256k1</td><td>Active</td></tr>
      <tr><td><code>tz3</code></td><td>P-256 (NIST)</td><td>Active</td></tr>
      <tr><td><code>tz4</code></td><td>BLS12-381</td><td>Active (consensus)</td></tr>
      <tr><td><code>tz5</code></td><td>ML-DSA-44 (Dilithium)</td><td>In development</td></tr>
    </tbody>
  </table>

  <h2>The Transition Challenge</h2>
  <p>
    Migrating to post-quantum cryptography is not a simple algorithm swap.
    It requires:
  </p>
  <ul>
    <li><strong>Hybrid schemes:</strong> Running classical and PQC algorithms in parallel during the transition period</li>
    <li><strong>Key management:</strong> PQC keys are 10-50x larger, impacting storage and bandwidth</li>
    <li><strong>Performance testing:</strong> Signature generation and verification times differ significantly from classical algorithms</li>
    <li><strong>Protocol updates:</strong> Consensus mechanisms, smart contracts, and wallet software all need adaptation</li>
  </ul>

  <h2>Key Resources</h2>
  <ul>
    <li>NIST Post-Quantum Cryptography project</li>
    <li>Open Quantum Safe &mdash; open-source PQC implementations (liboqs)</li>
    <li>Tezos Improvement Proposals for tz5</li>
    <li>ETSI Quantum-Safe Cryptography working group</li>
  </ul>

</div>

<footer>
  <p>&copy; 2026 Pacific Quantum Systems &middot; Vancouver, BC</p>
</footer>

</body>
</html>



============================================================
# quantum-comms.html
============================================================

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quantum Communications — Pacific Quantum Systems</title>
  <meta name="description" content="Quantum key distribution, the Canadian quantum communications landscape, and building the classical-quantum software interface.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

<nav>
  <div class="nav-inner">
    <a href="index.html" class="logo">Pacific <span>Quantum</span> Systems</a>
    <button class="menu-toggle" onclick="document.querySelector('nav ul').classList.toggle('open')">&#9776;</button>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="research.html">Research</a></li>
      <li><a href="computational.html">Computation</a></li>
      <li><a href="pqc.html">Post-Quantum Crypto</a></li>
      <li><a href="quantum-comms.html" class="active">Quantum Comms</a></li>
      <li><a href="about.html">About</a></li>
    </ul>
  </div>
</nav>

<div class="page-header">
  <h1>Quantum Communications</h1>
  <p>Provably secure key distribution and the emerging quantum network infrastructure</p>
</div>

<div class="content">

  <h2>Quantum Key Distribution</h2>
  <p>
    Quantum Key Distribution (QKD) uses the fundamental properties of quantum
    mechanics to establish shared secret keys between two parties with
    information-theoretic security. Unlike post-quantum cryptography (which relies
    on computational hardness assumptions), QKD security is guaranteed by physics
    itself: any eavesdropper necessarily disturbs the quantum states and is detected.
  </p>

  <h3>Major QKD Protocols</h3>
  <table>
    <thead>
      <tr>
        <th>Protocol</th>
        <th>Year</th>
        <th>Approach</th>
        <th>Market Share</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>BB84</strong></td>
        <td>1984</td>
        <td>Prepare-and-measure, two conjugate bases</td>
        <td>~80%</td>
      </tr>
      <tr>
        <td><strong>E91</strong></td>
        <td>1991</td>
        <td>Entanglement-based, Bell inequality verification</td>
        <td>Research</td>
      </tr>
      <tr>
        <td><strong>CV-QKD</strong></td>
        <td>2000s</td>
        <td>Continuous-variable, coherent states</td>
        <td>Growing</td>
      </tr>
    </tbody>
  </table>

  <div class="callout">
    <p>
      <strong>Key insight:</strong> QKD protocols use photonic hardware for quantum
      state transmission, but classical software handles everything else &mdash;
      authentication, error correction, privacy amplification, key management,
      and network orchestration. The classical-quantum software interface is where
      engineering meets physics.
    </p>
  </div>

  <h2>The Canadian Quantum Landscape</h2>
  <p>
    Canada is positioning itself as a global leader in quantum communications
    through a combination of government programs, private companies, and
    university research groups.
  </p>

  <h3>Key Programs and Organizations</h3>

  <table>
    <thead>
      <tr>
        <th>Entity</th>
        <th>Location</th>
        <th>Focus</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>NRC QUIN</strong></td>
        <td>National</td>
        <td>Quantum Internetworking Challenge program (2026&ndash;2033), building Canada's quantum network infrastructure</td>
      </tr>
      <tr>
        <td><strong>Photonic Inc.</strong></td>
        <td>Vancouver, BC</td>
        <td>Silicon spin-photon qubits for distributed quantum computing; partnership with TELUS for commercial fiber networks</td>
      </tr>
      <tr>
        <td><strong>TELUS</strong></td>
        <td>Vancouver, BC</td>
        <td>Commercial fiber infrastructure for quantum communications deployment</td>
      </tr>
      <tr>
        <td><strong>SFU Q-Van Lab</strong></td>
        <td>Burnaby, BC</td>
        <td>Quantum Internet Systems Lab; Q-Van metropolitan testbed; QEYSSat satellite ground segment</td>
      </tr>
      <tr>
        <td><strong>Xanadu</strong></td>
        <td>Toronto, ON</td>
        <td>Canada Quantum Network (CQN) testbed; photonic quantum computing</td>
      </tr>
      <tr>
        <td><strong>QEYSSat</strong></td>
        <td>National / Space</td>
        <td>Canadian quantum communications satellite, launch expected late 2026</td>
      </tr>
    </tbody>
  </table>

  <h2>British Columbia Advantage</h2>
  <p>
    The Pacific Northwest offers a unique concentration of quantum communications
    capabilities:
  </p>
  <ul>
    <li><strong>Photonic Inc.</strong> &mdash; developing silicon-based quantum processors with native photonic interfaces ideal for networking</li>
    <li><strong>TELUS partnership</strong> &mdash; commercial-grade fiber infrastructure already in place for QKD deployment</li>
    <li><strong>SFU Q-Van testbed</strong> &mdash; metropolitan quantum network connecting campus locations</li>
    <li><strong>QEYSSat ground segment</strong> &mdash; SFU hosts a ground station for Canada's quantum satellite</li>
  </ul>

  <h2>Standards and Interfaces</h2>
  <p>
    The classical-quantum interface is defined by emerging standards that enable
    interoperability between QKD hardware from different vendors and integration
    with existing network infrastructure.
  </p>

  <table>
    <thead>
      <tr>
        <th>Standard</th>
        <th>Scope</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>ETSI QKD 014</code></td>
        <td>RESTful API for QKD key delivery (JSON/HTTPS) &mdash; the primary software interface</td>
      </tr>
      <tr>
        <td><code>ETSI QKD 004</code></td>
        <td>Application interface for QKD key consumption</td>
      </tr>
      <tr>
        <td><code>ITU-T Y.3800+</code></td>
        <td>Quantum network architecture framework</td>
      </tr>
    </tbody>
  </table>

  <h2>From Theory to Infrastructure</h2>
  <p>
    Deploying quantum communications requires solving problems at every layer:
  </p>
  <ul>
    <li><strong>Physical layer:</strong> Single-photon sources, detectors, and fiber/free-space channels</li>
    <li><strong>Protocol layer:</strong> QKD protocol implementation, error correction, privacy amplification</li>
    <li><strong>Key management:</strong> Storing, distributing, and rotating quantum-derived keys</li>
    <li><strong>Network orchestration:</strong> SDN controllers for routing, trusted-node relay, and network topology management</li>
    <li><strong>Application integration:</strong> Feeding QKD-derived keys into existing encryption systems (TLS, IPsec, VPNs)</li>
  </ul>

  <div class="callout">
    <p>
      <strong>NRC QUIN program</strong> (2026&ndash;2033) represents a $100M+ investment
      in building Canada's quantum network infrastructure. The Expression of Interest
      process opened in early 2026, with opportunities for testbed hosting,
      classical-quantum integration, and application development.
    </p>
  </div>

  <h2>Complementary Technologies</h2>
  <p>
    QKD and PQC are complementary, not competing:
  </p>
  <ul>
    <li><strong>QKD</strong> provides information-theoretic security for key exchange over dedicated channels</li>
    <li><strong>PQC</strong> provides computational security that works over any network without specialized hardware</li>
    <li>Future networks will likely use <strong>both</strong>: QKD for high-security links, PQC for general-purpose encryption</li>
  </ul>

</div>

<footer>
  <p>&copy; 2026 Pacific Quantum Systems &middot; Vancouver, BC</p>
</footer>

</body>
</html>



============================================================
# about.html
============================================================

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About — Pacific Quantum Systems</title>
  <meta name="description" content="About Pacific Quantum Systems and Michael Kernaghan's research in quantum foundations and cryptography.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

<nav>
  <div class="nav-inner">
    <a href="index.html" class="logo">Pacific <span>Quantum</span> Systems</a>
    <button class="menu-toggle" onclick="document.querySelector('nav ul').classList.toggle('open')">&#9776;</button>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="research.html">Research</a></li>
      <li><a href="computational.html">Computation</a></li>
      <li><a href="pqc.html">Post-Quantum Crypto</a></li>
      <li><a href="quantum-comms.html">Quantum Comms</a></li>
      <li><a href="about.html" class="active">About</a></li>
    </ul>
  </div>
</nav>

<div class="page-header">
  <h1>About</h1>
  <p>Research at the intersection of quantum foundations, cryptography, and communications</p>
</div>

<div class="content">

  <h2>Pacific Quantum Systems</h2>
  <p>
    Pacific Quantum Systems is a research initiative based in Vancouver, British
    Columbia, focused on the mathematical and computational structures that connect
    quantum foundations to practical quantum technologies.
  </p>
  <p>
    Our work spans three interconnected domains: the algebraic classification of
    quantum contextuality (understanding <em>why</em> quantum mechanics enables
    advantages over classical systems), post-quantum cryptography (building
    defences against quantum attacks), and quantum communications (deploying
    physics-based security for network infrastructure).
  </p>

  <h2>Michael Kernaghan</h2>
  <p>
    Michael Kernaghan is an independent researcher with a background in quantum
    foundations dating to the 1990s. His early work on Kochen-Specker sets
    produced landmark results that remain widely cited in the contextuality
    literature:
  </p>
  <ul>
    <li>
      <strong>The 20-vector KS set</strong> (1994) &mdash; the first proof that
      20 vectors suffice for a Kochen-Specker contradiction in four dimensions,
      published in <em>Journal of Physics A</em>.
    </li>
    <li>
      <strong>The Kernaghan-Peres 40-vector construction</strong> (1995) &mdash;
      a KS set in eight dimensions (three qubits) that connects directly to
      GHZ paradoxes, published in <em>Physics Letters A</em> with Asher Peres.
    </li>
  </ul>
  <p>
    Current work extends these foundations into computational algebraic number
    theory, classifying for the first time which algebraic rings support
    Kochen-Specker constructions in dimension three.
  </p>

  <h2>Selected Publications</h2>
  <table>
    <thead>
      <tr>
        <th>Year</th>
        <th>Publication</th>
        <th>Venue</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>2026</td>
        <td>The Algebraic Landscape of Kochen-Specker Sets in Dimension Three</td>
        <td><em>In preparation (PRA)</em></td>
      </tr>
      <tr>
        <td>2026</td>
        <td>New KS Sets from Algebraic Number Fields with Enhanced Contextual Advantage</td>
        <td><em>In preparation (PRL)</em></td>
      </tr>
      <tr>
        <td>2026</td>
        <td>Graph Universality of CK-31 and the Norm-2 Boundary</td>
        <td><em>In preparation (PRL)</em></td>
      </tr>
      <tr>
        <td>1995</td>
        <td>Kochen-Specker theorem for eight-dimensional space</td>
        <td><em>Phys. Lett. A</em> <strong>198</strong>, 1&ndash;5</td>
      </tr>
      <tr>
        <td>1994</td>
        <td>Bell-Kochen-Specker theorem for 20 vectors</td>
        <td><em>J. Phys. A</em> <strong>27</strong>, L829</td>
      </tr>
    </tbody>
  </table>

  <h2>Research Approach</h2>
  <p>
    Our methodology combines:
  </p>
  <ul>
    <li><strong>Computational exploration:</strong> Systematic search and classification using SAT solvers, graph algorithms, and algebraic number theory</li>
    <li><strong>Mathematical proof:</strong> Rigorous verification of computational discoveries</li>
    <li><strong>Applied context:</strong> Connecting foundational results to practical quantum technologies</li>
  </ul>
  <p>
    All computational work uses reproducible methods with fixed random seeds,
    and results are verified independently using multiple algorithmic approaches
    (SAT, integer linear programming, direct enumeration).
  </p>

  <h2>Location</h2>
  <p>
    Based in Vancouver, British Columbia &mdash; at the centre of Canada's
    Pacific quantum technology corridor, home to Photonic Inc., TELUS quantum
    communications initiatives, and SFU's Quantum Internet Systems Lab.
  </p>

  <h2>Contact</h2>
  <p>
    For research inquiries, collaboration proposals, or questions about our work,
    please reach out via the channels below.
  </p>
  <ul>
    <li>GitHub: <a href="https://github.com/michaelkernaghan">github.com/michaelkernaghan</a></li>
  </ul>

</div>

<footer>
  <p>&copy; 2026 Pacific Quantum Systems &middot; Vancouver, BC</p>
</footer>

</body>
</html>



============================================================
# css/style.css
============================================================

/* Pacific Quantum Systems — Clean Modern Design */

:root {
  --bg: #0a0e17;
  --bg-card: #111827;
  --bg-card-hover: #1a2332;
  --text: #e2e8f0;
  --text-muted: #94a3b8;
  --accent: #06b6d4;
  --accent-dim: rgba(6, 182, 212, 0.15);
  --accent-bright: #22d3ee;
  --border: #1e293b;
  --font: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
  --font-mono: 'JetBrains Mono', 'Fira Code', monospace;
  --max-width: 1100px;
  --radius: 8px;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {
  font-family: var(--font);
  background: var(--bg);
  color: var(--text);
  line-height: 1.7;
  font-size: 16px;
  min-height: 100vh;
}

a { color: var(--accent); text-decoration: none; transition: color 0.2s; }
a:hover { color: var(--accent-bright); }

/* Navigation */
nav {
  position: sticky;
  top: 0;
  z-index: 100;
  background: rgba(10, 14, 23, 0.85);
  backdrop-filter: blur(16px);
  border-bottom: 1px solid var(--border);
  padding: 0 2rem;
}

nav .nav-inner {
  max-width: var(--max-width);
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 64px;
}

nav .logo {
  font-size: 1.1rem;
  font-weight: 700;
  color: var(--text);
  letter-spacing: -0.02em;
}

nav .logo span { color: var(--accent); }

nav ul {
  list-style: none;
  display: flex;
  gap: 2rem;
}

nav ul a {
  color: var(--text-muted);
  font-size: 0.9rem;
  font-weight: 500;
  transition: color 0.2s;
}

nav ul a:hover,
nav ul a.active { color: var(--accent); }

/* Hamburger menu for mobile */
.menu-toggle { display: none; background: none; border: none; color: var(--text); font-size: 1.5rem; cursor: pointer; }

/* Hero */
.hero {
  max-width: var(--max-width);
  margin: 0 auto;
  padding: 6rem 2rem 4rem;
}

.hero h1 {
  font-size: clamp(2.2rem, 5vw, 3.5rem);
  font-weight: 800;
  line-height: 1.15;
  letter-spacing: -0.03em;
  margin-bottom: 1.5rem;
}

.hero h1 .highlight {
  background: linear-gradient(135deg, var(--accent), #818cf8);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero .subtitle {
  font-size: 1.2rem;
  color: var(--text-muted);
  max-width: 640px;
  margin-bottom: 2rem;
}

/* Page header (inner pages) */
.page-header {
  max-width: var(--max-width);
  margin: 0 auto;
  padding: 4rem 2rem 2rem;
  border-bottom: 1px solid var(--border);
  margin-bottom: 3rem;
}

.page-header h1 {
  font-size: 2.2rem;
  font-weight: 800;
  letter-spacing: -0.02em;
  margin-bottom: 0.5rem;
}

.page-header p {
  color: var(--text-muted);
  font-size: 1.1rem;
}

/* Content */
.content {
  max-width: var(--max-width);
  margin: 0 auto;
  padding: 0 2rem 4rem;
}

/* Cards grid */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin-bottom: 3rem;
}

.card {
  background: var(--bg-card);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 2rem;
  transition: background 0.2s, border-color 0.2s;
}

.card:hover {
  background: var(--bg-card-hover);
  border-color: var(--accent);
}

.card .icon {
  font-size: 1.8rem;
  margin-bottom: 1rem;
  display: block;
}

.card h3 {
  font-size: 1.15rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
}

.card p {
  color: var(--text-muted);
  font-size: 0.95rem;
}

/* Pillar cards on home */
.pillar-link { display: block; }

/* Section headings */
.content h2 {
  font-size: 1.6rem;
  font-weight: 700;
  margin: 2.5rem 0 1rem;
  letter-spacing: -0.01em;
}

.content h3 {
  font-size: 1.2rem;
  font-weight: 600;
  margin: 2rem 0 0.75rem;
}

.content p, .content li {
  color: var(--text-muted);
  margin-bottom: 0.75rem;
}

.content ul, .content ol {
  padding-left: 1.5rem;
}

/* Tables */
table {
  width: 100%;
  border-collapse: collapse;
  margin: 1.5rem 0;
  font-size: 0.9rem;
}

th, td {
  text-align: left;
  padding: 0.75rem 1rem;
  border-bottom: 1px solid var(--border);
}

th {
  color: var(--accent);
  font-weight: 600;
  font-size: 0.85rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

td { color: var(--text-muted); }

/* Code / math */
code, .math {
  font-family: var(--font-mono);
  font-size: 0.9em;
  background: var(--accent-dim);
  padding: 0.15em 0.4em;
  border-radius: 4px;
  color: var(--accent-bright);
}

pre {
  background: var(--bg-card);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 1.5rem;
  overflow-x: auto;
  margin: 1rem 0;
}

pre code { background: none; padding: 0; }

/* Callout boxes */
.callout {
  background: var(--accent-dim);
  border-left: 3px solid var(--accent);
  border-radius: 0 var(--radius) var(--radius) 0;
  padding: 1.25rem 1.5rem;
  margin: 1.5rem 0;
}

.callout p { color: var(--text); margin-bottom: 0; }

/* Badge */
.badge {
  display: inline-block;
  font-size: 0.75rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  background: var(--accent-dim);
  color: var(--accent);
  padding: 0.2em 0.6em;
  border-radius: 4px;
  margin-bottom: 0.75rem;
}

/* Footer */
footer {
  border-top: 1px solid var(--border);
  padding: 2rem;
  text-align: center;
  color: var(--text-muted);
  font-size: 0.85rem;
}

footer a { color: var(--text-muted); }
footer a:hover { color: var(--accent); }

/* Responsive */
@media (max-width: 768px) {
  nav ul { display: none; }
  .menu-toggle { display: block; }
  nav ul.open {
    display: flex;
    flex-direction: column;
    position: absolute;
    top: 64px;
    left: 0;
    right: 0;
    background: var(--bg);
    border-bottom: 1px solid var(--border);
    padding: 1rem 2rem;
    gap: 1rem;
  }
  .hero { padding: 4rem 1.5rem 3rem; }
  .content { padding: 0 1.5rem 3rem; }
  .cards { grid-template-columns: 1fr; }
}



============================================================
# netlify.toml
============================================================

[build]
  publish = "."

[[headers]]
  for = "/*"
  [headers.values]
    X-Frame-Options = "DENY"
    X-Content-Type-Options = "nosniff"
    Referrer-Policy = "strict-origin-when-cross-origin"

