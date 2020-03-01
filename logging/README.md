[![Video: Logging][img]][vid]

[vid]: https://youtu.be/l-EKrlcNhNI
[img]: https://img.youtube.com/vi/l-EKrlcNhNI/hqdefault.jpg

*Summary:* Another part of accountability is logging. This is important
to detect attacks by analysing how events transpired.

*Intended learning outcomes:* In particular, the <span
acronym-label="ILO" acronym-form="plural+short">ILOs</span> are that you
are able to:

-   *evaluate* advantages and disadvantages of different approaches to
    audit trails,

-   *analyse* a situation and *design* proper logging.

*Reading:* Anderson describes logging (or audit trails) in Chapter 10
“Banking and Bookkeeping” in  (Anderson 2008). We will also discuss the
secure logging system of Schneier and Kelsey (1999) (Schneier and Kelsey
1999) as an example of how to achieve secure logging in a challenging
environment. The construction described therein is a method to safely
store audit logs in an untrusted machine; in the scheme, all log entries
generated prior to a compromise will be impossible for the attacker to
read, modify, or destroy undetectably.

Anderson, Ross J. 2008. *Security Engineering: A Guide to Building
Dependable Distributed Systems*. 2nd ed. Indianapolis, IN: Wiley.
<http://www.cl.cam.ac.uk/~rja14/book.html>.

Schneier, Bruce, and John Kelsey. 1999. “Secure Audit Logs to Support
Computer Forensics.” *ACM Transactions on Information and System
Security (TISSEC)* 2 (2): 159–76.
