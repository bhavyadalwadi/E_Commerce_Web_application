# Primary App

## Responsibility
Main runtime for `E_Commerce_Web_application`.

## Dependencies
- Java
- JSP
- Servlets
- Tomcat
- MySQL
- XAMPP

## Inbound APIs
- No formal inbound API is visible.

## Outbound APIs
- No confirmed external provider or downstream API.

## Databases Used
- MySQL

## Queues / Topics
- No queue/topic layer visible.

## Critical Workflows
- Product and cart detail flows around CartDetails and ProductDetails
- Session-backed shopping flow through SessionBean
- Authentication and controller layers
- Database-backed product/cart state using the `cart` schema
- JSP-based web front end served through Tomcat

## Failure Modes
- Project maturity is uneven; expect weaker docs, less automation, and more manual assumptions than the active product repos.

## Scaling Concerns
- current implementation appears intentionally lightweight
- there is no evidence of multi-service scaling machinery unless repo docs add it

## Operational Concerns
- start from repo-local `.claude/` docs and Graphify summary before code changes
- validate environment assumptions before debugging logic

## Important Source Files
- `easy_online_shop/WebContent/index.jsp`
- `easy_online_shop/src`
- `Readme file.txt`

## Dangerous Code Paths
- Project maturity is uneven; expect weaker docs, less automation, and more manual assumptions than the active product repos.

## Testing Strategy
- No standardized automated test command is visible.

## Known Technical Debt
- Pending work is unknown from current repo docs.
