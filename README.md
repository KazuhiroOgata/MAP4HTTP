# MAP4HTTP
Maude Specs for Formal Analysis of Mutual Authentication Protocol for HTTP Proposed in IETF RFC 8120
(1) DH.maude - Spec of the DH Key Exchange Protocol.
(2) map4http.maude - Spec of the RFC 8120 Protocol under the assumption that the cruptosystem used is perfect.
(3) map4http-leak-cr.maude - Spec of the RFC 8120 Protocol under the assumption that random numbers generated by clients are leaked to the intruder.
(4) map4http-leak-sr.maude - Spec of the RFC 8120 Protocol under the assumption that random numbers generated by servers are leaked to the intruder; K-SEC, C-CORR and S-CORR are model checked but No-NPA is not in this spec.
(5) map4http-leak-sr-NoMPA.maude - Spec of the RFC 8120 Protocol under the assumption that random numbers generated by servers are leaked to the intruder; No-NPA is model checked, finding a counterexample for No-MPA.
(6) map4http-revised.maude - Spec of the RFC 8120 Protocol revised.
(7) map4http-OTPW.maude - Spec of the RFC 8120 Protocol revised in which the Lamport one-time password scheme is used
