# Awesome Python HTTP Clients [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Python HTTP client libraries, from high-level clients to low-level protocol implementations.

## Top 20 by GitHub Stars

| # | Project | Stars |
|---|---------|-------|
| 1 | [curl_cffi](https://github.com/lexiforest/curl_cffi) | ![Stars](https://img.shields.io/github/stars/lexiforest/curl_cffi) |
| 2 | [requests-html](https://github.com/psf/requests-html) | ![Stars](https://img.shields.io/github/stars/psf/requests-html) |
| 3 | [tornado.httpclient](https://github.com/tornadoweb/tornado) | ![Stars](https://img.shields.io/github/stars/tornadoweb/tornado) |
| 4 | [requests](https://github.com/psf/requests) | ![Stars](https://img.shields.io/github/stars/psf/requests) |
| 5 | [aiohttp](https://github.com/aio-libs/aiohttp) | ![Stars](https://img.shields.io/github/stars/aio-libs/aiohttp) |
| 6 | [httpx](https://github.com/encode/httpx) | ![Stars](https://img.shields.io/github/stars/encode/httpx) |
| 7 | [MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) | ![Stars](https://img.shields.io/github/stars/MechanicalSoup/MechanicalSoup) |
| 8 | [grequests](https://github.com/spyoungtech/grequests) | ![Stars](https://img.shields.io/github/stars/spyoungtech/grequests) |
| 9 | [urllib3](https://github.com/urllib3/urllib3) | ![Stars](https://img.shields.io/github/stars/urllib3/urllib3) |
| 10 | [curl-impersonate](https://github.com/lexiforest/curl-impersonate) | ![Stars](https://img.shields.io/github/stars/lexiforest/curl-impersonate) |
| 11 | [requests-cache](https://github.com/requests-cache/requests-cache) | ![Stars](https://img.shields.io/github/stars/requests-cache/requests-cache) |
| 12 | [requests-futures](https://github.com/ross/requests-futures) | ![Stars](https://img.shields.io/github/stars/ross/requests-futures) |
| 13 | [niquests](https://github.com/jawah/niquests) | ![Stars](https://img.shields.io/github/stars/jawah/niquests) |
| 14 | [geventhttpclient](https://github.com/geventhttpclient/geventhttpclient) | ![Stars](https://img.shields.io/github/stars/geventhttpclient/geventhttpclient) |
| 15 | [httptools](https://github.com/MagicStack/httptools) | ![Stars](https://img.shields.io/github/stars/MagicStack/httptools) |
| 16 | [pycurl](https://github.com/pycurl/pycurl) | ![Stars](https://img.shields.io/github/stars/pycurl/pycurl) |
| 17 | [hyper](https://github.com/python-hyper/hyper) | ![Stars](https://img.shields.io/github/stars/python-hyper/hyper) |
| 18 | [h2](https://github.com/python-hyper/h2) | ![Stars](https://img.shields.io/github/stars/python-hyper/h2) |
| 19 | [requests-toolbelt](https://github.com/requests/toolbelt) | ![Stars](https://img.shields.io/github/stars/requests/toolbelt) |
| 20 | [requests-oauthlib](https://github.com/requests/requests-oauthlib) | ![Stars](https://img.shields.io/github/stars/requests/requests-oauthlib) |

## Contents

- [General-Purpose Clients](#general-purpose-clients)
- [Async-First Clients](#async-first-clients)
- [Concurrency Wrappers](#concurrency-wrappers)
- [Low-Level and Transport Clients](#low-level-and-transport-clients)
- [Protocol Implementations](#protocol-implementations)
- [Scraping and Fingerprinting Clients](#scraping-and-fingerprinting-clients)
- [Declarative and Specialized Clients](#declarative-and-specialized-clients)
- [Client Extensions and Tooling](#client-extensions-and-tooling)
- [Deprecated but Influential](#deprecated-but-influential)
- [Contributing](#contributing)

## General-Purpose Clients

<table>
<thead>
<tr>
<th>Project</th>
<th>Stars</th>
<th>Language</th>
<th>Features</th>
<th>Project Health</th>
</tr>
</thead>
<tbody>

<tr>
<td><a href="https://github.com/psf/requests">requests</a></td>
<td><img src="https://img.shields.io/github/stars/psf/requests" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Keep-Alive and connection pooling</li>
<li>Sessions with cookie persistence</li>
<li>Browser-style TLS/SSL verification</li>
<li>Basic and Digest authentication</li>
<li>Automatic content decompression and decoding</li>
<li>Multi-part file uploads</li>
<li>SOCKS proxy support</li>
<li>Streaming downloads</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/psf/requests" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/psf/requests" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/psf/requests" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/psf/requests/run-tests.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/psf/requests" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/psf/requests" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/psf/requests" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/encode/httpx">httpx</a></td>
<td><img src="https://img.shields.io/github/stars/encode/httpx" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Broadly compatible with the requests API</li>
<li>HTTP/1.1 and HTTP/2 support</li>
<li>Both sync and async API</li>
<li>Fully type-annotated</li>
<li>Timeout configuration at every level</li>
<li>Direct requests and client sessions</li>
<li>Built on httpcore for low-level transport</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/encode/httpx" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/encode/httpx" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/encode/httpx" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/encode/httpx/test-suite.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/encode/httpx" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/encode/httpx" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/encode/httpx" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/jawah/niquests">niquests</a></td>
<td><img src="https://img.shields.io/github/stars/jawah/niquests" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Drop-in replacement for requests</li>
<li>HTTP/1.1, HTTP/2, and HTTP/3 over QUIC</li>
<li>Both synchronous and asynchronous support</li>
<li>DNS over HTTPS, TLS, QUIC, and DNSSEC</li>
<li>Certificate revocation protection (OCSP)</li>
<li>Connection multiplexing</li>
<li>WebSocket support over HTTP/1, HTTP/2, HTTP/3</li>
<li>Server-Sent Events (SSE) support</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/jawah/niquests" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/jawah/niquests" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/jawah/niquests" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/jawah/niquests/run-tests.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/jawah/niquests" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/jawah/niquests" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/jawah/niquests" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/urllib3/urllib3">urllib3</a></td>
<td><img src="https://img.shields.io/github/stars/urllib3/urllib3" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Thread-safe connection pooling</li>
<li>Client-side TLS/SSL verification</li>
<li>File uploads with multipart encoding</li>
<li>Retry logic with backoff</li>
<li>HTTP/HTTPS proxy support</li>
<li>100% test coverage</li>
<li>Foundation library for requests and pip</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/urllib3/urllib3" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/urllib3/urllib3" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/urllib3/urllib3" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/urllib3/urllib3/ci.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/urllib3/urllib3" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/urllib3/urllib3" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/urllib3/urllib3" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/httplib2/httplib2">httplib2</a></td>
<td><img src="https://img.shields.io/github/stars/httplib2/httplib2" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Small, fast HTTP client library</li>
<li>Persistent (keep-alive) connections</li>
<li>HTTP caching support</li>
<li>Automatic handling of redirects and compression</li>
<li>SSL/TLS certificate validation</li>
<li>Google App Engine support</li>
<li>Various authentication schemes</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/httplib2/httplib2" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/httplib2/httplib2" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/httplib2/httplib2" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/httplib2/httplib2/test.yaml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/httplib2/httplib2" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/httplib2/httplib2" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/httplib2/httplib2" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/pycurl/pycurl">pycurl</a></td>
<td><img src="https://img.shields.io/github/stars/pycurl/pycurl" alt="Stars"></td>
<td>Python / C</td>
<td>
<ul>
<li>Thin Python wrapper over libcurl</li>
<li>Supports all protocols libcurl supports</li>
<li>Very high performance (C-level speed)</li>
<li>Multi interface for concurrent transfers</li>
<li>Full access to libcurl options and callbacks</li>
<li>SSL/TLS with multiple backends</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/pycurl/pycurl" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/pycurl/pycurl" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/pycurl/pycurl" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/pycurl/pycurl/ci.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/pycurl/pycurl" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/pycurl/pycurl" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/pycurl/pycurl" alt="Release">
</td>
</tr>

</tbody>
</table>

## Async-First Clients

<table>
<thead>
<tr>
<th>Project</th>
<th>Stars</th>
<th>Language</th>
<th>Features</th>
<th>Project Health</th>
</tr>
</thead>
<tbody>

<tr>
<td><a href="https://github.com/aio-libs/aiohttp">aiohttp</a></td>
<td><img src="https://img.shields.io/github/stars/aio-libs/aiohttp" alt="Stars"></td>
<td>Python / Cython</td>
<td>
<ul>
<li>Asynchronous HTTP client for asyncio</li>
<li>Client-side WebSocket support</li>
<li>Streaming request and response bodies</li>
<li>Connection pooling via TCPConnector</li>
<li>Cookie jar with domain filtering</li>
<li>Multipart form data uploads</li>
<li>HTTP and SOCKS proxy support</li>
<li>Cython-accelerated HTTP parser</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/aio-libs/aiohttp" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/aio-libs/aiohttp" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/aio-libs/aiohttp" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/aio-libs/aiohttp/ci-cd.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/aio-libs/aiohttp" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/aio-libs/aiohttp" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/aio-libs/aiohttp" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/twisted/treq">treq</a></td>
<td><img src="https://img.shields.io/github/stars/twisted/treq" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Requests-like API built on Twisted</li>
<li>Fully asynchronous using Twisted Deferreds</li>
<li>Automatic content decoding</li>
<li>JSON request and response convenience methods</li>
<li>Multipart file uploads</li>
<li>Cookie support</li>
<li>Integrates with Twisted ecosystem</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/twisted/treq" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/twisted/treq" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/twisted/treq" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/twisted/treq/ci.yaml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/twisted/treq" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/twisted/treq" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/twisted/treq" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/theelous3/asks">asks</a></td>
<td><img src="https://img.shields.io/github/stars/theelous3/asks" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Async HTTP library inspired by requests</li>
<li>Supports trio and curio async frameworks</li>
<li>Requests-like API</li>
<li>Session support with connection pooling</li>
<li>Cookie persistence</li>
<li>Streaming responses</li>
<li>&#9888;&#65039; Largely unmaintained</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/theelous3/asks" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/theelous3/asks" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/theelous3/asks" alt="Commit activity"><br>
<img src="https://img.shields.io/github/issues/theelous3/asks" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/theelous3/asks" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/theelous3/asks" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/tornadoweb/tornado">tornado.httpclient</a></td>
<td><img src="https://img.shields.io/github/stars/tornadoweb/tornado" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Async HTTP client (AsyncHTTPClient) with configurable implementations</li>
<li>SimpleAsyncHTTPClient (pure-Python) and CurlAsyncHTTPClient (libcurl)</li>
<li>HTTP/1.x and HTTP/2 support (via curl backend)</li>
<li>Streaming request and response body support</li>
<li>Automatic redirect following and authentication</li>
<li>Proxy support</li>
<li>Part of the mature Tornado async networking framework</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/tornadoweb/tornado" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/tornadoweb/tornado" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/tornadoweb/tornado" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/tornadoweb/tornado/test.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/tornadoweb/tornado" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/tornadoweb/tornado" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/tornadoweb/tornado" alt="Release">
</td>
</tr>

</tbody>
</table>

## Concurrency Wrappers

<table>
<thead>
<tr>
<th>Project</th>
<th>Stars</th>
<th>Language</th>
<th>Features</th>
<th>Project Health</th>
</tr>
</thead>
<tbody>

<tr>
<td><a href="https://github.com/ross/requests-futures">requests-futures</a></td>
<td><img src="https://img.shields.io/github/stars/ross/requests-futures" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Wraps requests with concurrent.futures</li>
<li>Returns Future objects instead of Response</li>
<li>Uses ThreadPoolExecutor (default 8 workers)</li>
<li>Also supports ProcessPoolExecutor</li>
<li>Accepts existing requests.Session objects</li>
<li>Background callbacks via background_callback parameter</li>
<li>Minimal API changes from standard requests</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/ross/requests-futures" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/ross/requests-futures" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/ross/requests-futures" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/ross/requests-futures/main.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/ross/requests-futures" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/ross/requests-futures" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/ross/requests-futures" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/spyoungtech/grequests">grequests</a></td>
<td><img src="https://img.shields.io/github/stars/spyoungtech/grequests" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Combines Requests with Gevent for async HTTP</li>
<li>Batch requests via grequests.map() for parallel execution</li>
<li>imap() returns a generator for lazy/streaming results</li>
<li>Custom exception handlers per request</li>
<li>Configurable gevent pool size</li>
<li>Uses the standard Requests API</li>
<li>Simple one-liner for sending multiple requests concurrently</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/spyoungtech/grequests" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/spyoungtech/grequests" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/spyoungtech/grequests" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/spyoungtech/grequests/test.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/spyoungtech/grequests" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/spyoungtech/grequests" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/spyoungtech/grequests" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/geventhttpclient/geventhttpclient">geventhttpclient</a></td>
<td><img src="https://img.shields.io/github/stars/geventhttpclient/geventhttpclient" alt="Stars"></td>
<td>Python / C</td>
<td>
<ul>
<li>High-performance concurrent HTTP client using gevent</li>
<li>Fast C-based HTTP parser (llhttp from Node.js)</li>
<li>HTTP/1.1 persistent connections and streaming</li>
<li>Requests-compatible interface (since v2.3)</li>
<li>httplib monkey-patching for compatibility</li>
<li>Safe SSL via certifi CA bundle by default</li>
<li>Designed for REST APIs and streaming APIs</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/geventhttpclient/geventhttpclient" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/geventhttpclient/geventhttpclient" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/geventhttpclient/geventhttpclient" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/geventhttpclient/geventhttpclient/test.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/geventhttpclient/geventhttpclient" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/geventhttpclient/geventhttpclient" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/geventhttpclient/geventhttpclient" alt="Release">
</td>
</tr>

</tbody>
</table>

## Low-Level and Transport Clients

<table>
<thead>
<tr>
<th>Project</th>
<th>Stars</th>
<th>Language</th>
<th>Features</th>
<th>Project Health</th>
</tr>
</thead>
<tbody>

<tr>
<td><a href="https://github.com/encode/httpcore">httpcore</a></td>
<td><img src="https://img.shields.io/github/stars/encode/httpcore" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Minimal, low-level HTTP client</li>
<li>HTTP/1.1 and HTTP/2 support</li>
<li>Both sync and async interfaces</li>
<li>Connection pooling</li>
<li>Extensible transport API</li>
<li>SOCKS proxy support</li>
<li>Fully type-annotated</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/encode/httpcore" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/encode/httpcore" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/encode/httpcore" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/encode/httpcore/test-suite.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/encode/httpcore" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/encode/httpcore" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/encode/httpcore" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/jawah/urllib3.future">urllib3.future</a></td>
<td><img src="https://img.shields.io/github/stars/jawah/urllib3.future" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Drop-in replacement fork of urllib3</li>
<li>HTTP/1.1, HTTP/2, and HTTP/3 support</li>
<li>Both sync and async (asyncio) APIs</li>
<li>Thread-safe and task-safe connection pooling</li>
<li>DNS over UDP, TLS, QUIC, or HTTPS with DNSSEC</li>
<li>Happy Eyeballs connection algorithm</li>
<li>Supports gzip, deflate, brotli, and zstd encoding</li>
<li>Post-quantum security support</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/jawah/urllib3.future" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/jawah/urllib3.future" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/jawah/urllib3.future" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/jawah/urllib3.future/ci.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/jawah/urllib3.future" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/jawah/urllib3.future" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/jawah/urllib3.future" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/MagicStack/httptools">httptools</a></td>
<td><img src="https://img.shields.io/github/stars/MagicStack/httptools" alt="Stars"></td>
<td>Python / C</td>
<td>
<ul>
<li>Python binding for the Node.js HTTP parser (llhttp)</li>
<li>HttpRequestParser and HttpResponseParser classes</li>
<li>URL parsing via parse_url()</li>
<li>Callback-based API (on_url, on_header, on_body, etc.)</li>
<li>Very high performance (C-based parsing)</li>
<li>Used internally by uvicorn and other ASGI servers</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/MagicStack/httptools" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/MagicStack/httptools" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/MagicStack/httptools" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/MagicStack/httptools/tests.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/MagicStack/httptools" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/MagicStack/httptools" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/MagicStack/httptools" alt="Release">
</td>
</tr>

</tbody>
</table>

## Protocol Implementations

<table>
<thead>
<tr>
<th>Project</th>
<th>Stars</th>
<th>Language</th>
<th>Features</th>
<th>Project Health</th>
</tr>
</thead>
<tbody>

<tr>
<td><a href="https://github.com/python-hyper/h11">h11</a></td>
<td><img src="https://img.shields.io/github/stars/python-hyper/h11" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Pure-Python HTTP/1.1 protocol implementation</li>
<li>Bring-your-own-I/O design (zero I/O code)</li>
<li>Works with any network API (sync, asyncio, trio)</li>
<li>Symmetric API: same events for client and server</li>
<li>State machine tracks connection lifecycle</li>
<li>Event-based parsing (Request, Response, Data, EndOfMessage)</li>
<li>Used by httpcore, uvicorn, and other modern stacks</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/python-hyper/h11" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/python-hyper/h11" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/python-hyper/h11" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/python-hyper/h11/ci.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/python-hyper/h11" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/python-hyper/h11" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/python-hyper/h11" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/python-hyper/h2">h2</a></td>
<td><img src="https://img.shields.io/github/stars/python-hyper/h2" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Pure-Python HTTP/2 protocol stack</li>
<li>Bring-your-own-I/O design</li>
<li>Supports both client and server use</li>
<li>Stream multiplexing</li>
<li>Flow control management</li>
<li>HPACK header compression</li>
<li>Embeddable in any Python program regardless of I/O paradigm</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/python-hyper/h2" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/python-hyper/h2" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/python-hyper/h2" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/python-hyper/h2/ci.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/python-hyper/h2" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/python-hyper/h2" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/python-hyper/h2" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/python-hyper/wsproto">wsproto</a></td>
<td><img src="https://img.shields.io/github/stars/python-hyper/wsproto" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Pure-Python WebSocket protocol stack</li>
<li>Sans-I/O state-machine design</li>
<li>Full RFC 6455 (WebSocket) support</li>
<li>RFC 7692 Compression Extensions support</li>
<li>Supports both client and server roles</li>
<li>Embeddable in any programming paradigm</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/python-hyper/wsproto" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/python-hyper/wsproto" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/python-hyper/wsproto" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/python-hyper/wsproto/ci.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/python-hyper/wsproto" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/python-hyper/wsproto" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/python-hyper/wsproto" alt="Release">
</td>
</tr>

</tbody>
</table>

## Scraping and Fingerprinting Clients

<table>
<thead>
<tr>
<th>Project</th>
<th>Stars</th>
<th>Language</th>
<th>Features</th>
<th>Project Health</th>
</tr>
</thead>
<tbody>

<tr>
<td><a href="https://github.com/lexiforest/curl_cffi">curl_cffi</a></td>
<td><img src="https://img.shields.io/github/stars/lexiforest/curl_cffi" alt="Stars"></td>
<td>Python / C</td>
<td>
<ul>
<li>Python binding for curl-impersonate via cffi</li>
<li>Impersonate browser TLS/JA3/HTTP2 fingerprints</li>
<li>Requests-like API</li>
<li>HTTP/2 and HTTP/3 support</li>
<li>Async support (asyncio and trio)</li>
<li>Bypasses TLS fingerprinting-based bot detection</li>
<li>WebSocket support</li>
<li>Pre-compiled wheels (no local compilation needed)</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/lexiforest/curl_cffi" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/lexiforest/curl_cffi" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/lexiforest/curl_cffi" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/lexiforest/curl_cffi/build-and-test.yaml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/lexiforest/curl_cffi" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/lexiforest/curl_cffi" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/lexiforest/curl_cffi" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/lexiforest/curl-impersonate">curl-impersonate</a></td>
<td><img src="https://img.shields.io/github/stars/lexiforest/curl-impersonate" alt="Stars"></td>
<td>C</td>
<td>
<ul>
<li>Patched curl that impersonates browser TLS/HTTP fingerprints</li>
<li>Chrome, Edge, Safari, Firefox fingerprint support</li>
<li>Compiled with BoringSSL for browser-identical TLS handshakes</li>
<li>HTTP/2 and HTTP/3 fingerprint support (QUIC)</li>
<li>ECH, ZSTD compression, post-quantum curve support</li>
<li>Core engine behind Python's curl_cffi library</li>
<li>Available as CLI tool or library (libcurl replacement)</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/lexiforest/curl-impersonate" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/lexiforest/curl-impersonate" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/lexiforest/curl-impersonate" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/lexiforest/curl-impersonate/build.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/lexiforest/curl-impersonate" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/lexiforest/curl-impersonate" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/lexiforest/curl-impersonate" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/MechanicalSoup/MechanicalSoup">MechanicalSoup</a></td>
<td><img src="https://img.shields.io/github/stars/MechanicalSoup/MechanicalSoup" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Automates website interaction (browser-like)</li>
<li>Built on top of Requests and BeautifulSoup</li>
<li>Automatic form filling and submission</li>
<li>Follows links programmatically</li>
<li>Cookie and session management</li>
<li>Lightweight alternative to Selenium for non-JS sites</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/MechanicalSoup/MechanicalSoup" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/MechanicalSoup/MechanicalSoup" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/MechanicalSoup/MechanicalSoup" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/MechanicalSoup/MechanicalSoup/python-package.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/MechanicalSoup/MechanicalSoup" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/MechanicalSoup/MechanicalSoup" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/MechanicalSoup/MechanicalSoup" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/psf/requests-html">requests-html</a></td>
<td><img src="https://img.shields.io/github/stars/psf/requests-html" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>HTML parsing built on top of requests</li>
<li>Full JavaScript rendering via Chromium</li>
<li>CSS selectors (jQuery-style via PyQuery)</li>
<li>XPath selectors</li>
<li>Automatic redirect following</li>
<li>Connection pooling and cookie persistence</li>
<li>Async support via AsyncHTMLSession</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/psf/requests-html" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/psf/requests-html" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/psf/requests-html" alt="Commit activity"><br>
<img src="https://img.shields.io/github/issues/psf/requests-html" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/psf/requests-html" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/psf/requests-html" alt="Release">
</td>
</tr>

</tbody>
</table>

## Declarative and Specialized Clients

<table>
<thead>
<tr>
<th>Project</th>
<th>Stars</th>
<th>Language</th>
<th>Features</th>
<th>Project Health</th>
</tr>
</thead>
<tbody>

<tr>
<td><a href="https://github.com/prkumar/uplink">uplink</a></td>
<td><img src="https://img.shields.io/github/stars/prkumar/uplink" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Declarative HTTP client inspired by Retrofit</li>
<li>Define API clients using decorators and type hints</li>
<li>Pluggable backends: requests, aiohttp, Twisted</li>
<li>Built-in serialization (marshmallow, pydantic)</li>
<li>Middleware and interceptor support</li>
<li>Basic authentication built-in</li>
<li>Multipart uploads and URL path replacement</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/prkumar/uplink" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/prkumar/uplink" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/prkumar/uplink" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/prkumar/uplink/ci.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/prkumar/uplink" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/prkumar/uplink" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/prkumar/uplink" alt="Release">
</td>
</tr>

</tbody>
</table>

## Client Extensions and Tooling

<table>
<thead>
<tr>
<th>Project</th>
<th>Stars</th>
<th>Language</th>
<th>Features</th>
<th>Project Health</th>
</tr>
</thead>
<tbody>

<tr>
<td><a href="https://github.com/requests/toolbelt">requests-toolbelt</a></td>
<td><img src="https://img.shields.io/github/stars/requests/toolbelt" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Official collection of utilities for python-requests</li>
<li>Streaming multipart/form-data encoder (MultipartEncoder)</li>
<li>User-Agent string constructor</li>
<li>SSLAdapter for choosing SSL/TLS protocol versions</li>
<li>AuthHandler for domain-based auth dispatch</li>
<li>Streaming multipart upload with progress monitoring</li>
<li>Session with ordered/forced cookie handling</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/requests/toolbelt" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/requests/toolbelt" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/requests/toolbelt" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/requests/toolbelt/ci.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/requests/toolbelt" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/requests/toolbelt" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/requests/toolbelt" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/requests-cache/requests-cache">requests-cache</a></td>
<td><img src="https://img.shields.io/github/stars/requests-cache/requests-cache" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Transparent persistent HTTP cache for requests</li>
<li>Multiple backends: SQLite, Redis, MongoDB, DynamoDB, filesystem</li>
<li>Expiration/TTL control with URL-pattern-based rules</li>
<li>Drop-in replacement via CachedSession or monkeypatching</li>
<li>Serialization options (JSON, BSON, pickle)</li>
<li>Cache filtering and conditional request support</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/requests-cache/requests-cache" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/requests-cache/requests-cache" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/requests-cache/requests-cache" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/requests-cache/requests-cache/build.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/requests-cache/requests-cache" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/requests-cache/requests-cache" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/requests-cache/requests-cache" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/karpetrosyan/hishel">hishel</a></td>
<td><img src="https://img.shields.io/github/stars/karpetrosyan/hishel" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>RFC 9111 compliant HTTP caching</li>
<li>Drop-in integration with HTTPX, Requests, and ASGI frameworks</li>
<li>SQLite storage backend</li>
<li>Full async and sync support</li>
<li>Streaming support for large payloads</li>
<li>GraphQL query caching (body-sensitive)</li>
<li>Fully typed with comprehensive type hints</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/karpetrosyan/hishel" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/karpetrosyan/hishel" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/karpetrosyan/hishel" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/karpetrosyan/hishel/ci.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/karpetrosyan/hishel" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/karpetrosyan/hishel" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/karpetrosyan/hishel" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/requests/requests-oauthlib">requests-oauthlib</a></td>
<td><img src="https://img.shields.io/github/stars/requests/requests-oauthlib" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>First-class OAuth library support for Requests</li>
<li>OAuth 1 workflow support</li>
<li>OAuth 2 workflow support (Authorization Code Grant)</li>
<li>Built on top of OAuthlib</li>
<li>Simple session-based API (OAuth1Session, OAuth2Session)</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/requests/requests-oauthlib" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/requests/requests-oauthlib" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/requests/requests-oauthlib" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/requests/requests-oauthlib/run-tests.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/requests/requests-oauthlib" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/requests/requests-oauthlib" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/requests/requests-oauthlib" alt="Release">
</td>
</tr>

<tr>
<td><a href="https://github.com/requests/requests-kerberos">requests-kerberos</a></td>
<td><img src="https://img.shields.io/github/stars/requests/requests-kerberos" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Kerberos/GSSAPI authentication for Requests</li>
<li>Mutual authentication (REQUIRED, OPTIONAL, DISABLED)</li>
<li>Works with credential cache or explicit principal/password</li>
<li>Supports full requests.api surface</li>
<li>Sanitize option for mutual auth error responses</li>
<li>Cross-platform (Linux, macOS, Windows)</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/requests/requests-kerberos" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/requests/requests-kerberos" alt="Last commit"><br>
<img src="https://img.shields.io/github/commit-activity/m/requests/requests-kerberos" alt="Commit activity"><br>
<img src="https://img.shields.io/github/actions/workflow/status/requests/requests-kerberos/ci.yml" alt="Build"><br>
<img src="https://img.shields.io/github/issues/requests/requests-kerberos" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/requests/requests-kerberos" alt="PRs"><br>
<img src="https://img.shields.io/github/v/release/requests/requests-kerberos" alt="Release">
</td>
</tr>

</tbody>
</table>

## Deprecated but Influential

> These projects are archived or unmaintained but were historically important in shaping the Python HTTP client ecosystem.

<table>
<thead>
<tr>
<th>Project</th>
<th>Stars</th>
<th>Language</th>
<th>Notes</th>
<th>Project Health</th>
</tr>
</thead>
<tbody>

<tr>
<td><a href="https://github.com/python-hyper/hyper">hyper</a></td>
<td><img src="https://img.shields.io/github/stars/python-hyper/hyper" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Early HTTP/2 client for Python</li>
<li>Drop-in replacement API similar to http.client</li>
<li>Pioneered HTTP/2 support in the Python ecosystem</li>
<li>&#9888;&#65039; Archived — maintainers recommend httpx</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/python-hyper/hyper" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/python-hyper/hyper" alt="Last commit"><br>
<img src="https://img.shields.io/github/issues/python-hyper/hyper" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/python-hyper/hyper" alt="PRs">
</td>
</tr>

<tr>
<td><a href="https://github.com/encode/requests-async">requests-async</a></td>
<td><img src="https://img.shields.io/github/stars/encode/requests-async" alt="Stars"></td>
<td>Python</td>
<td>
<ul>
<li>Added async/await support to the requests library</li>
<li>Important stepping stone toward httpx</li>
<li>&#9888;&#65039; Archived — superseded by httpx</li>
</ul>
</td>
<td>
<img src="https://img.shields.io/github/stars/encode/requests-async" alt="Stars"><br>
<img src="https://img.shields.io/github/last-commit/encode/requests-async" alt="Last commit"><br>
<img src="https://img.shields.io/github/issues/encode/requests-async" alt="Issues"><br>
<img src="https://img.shields.io/github/issues-pr/encode/requests-async" alt="PRs">
</td>
</tr>

</tbody>
</table>

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.
