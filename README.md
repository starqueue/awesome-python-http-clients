# Awesome Python HTTP Clients [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Python HTTP client libraries.

## Contents

- [Libraries](#libraries)
- [Contributing](#contributing)

## Libraries

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
<td><a href="https://github.com/lexiforest/curl_cffi">curl_cffi</a></td>
<td><img src="https://img.shields.io/github/stars/lexiforest/curl_cffi" alt="Stars"></td>
<td>Python / C</td>
<td>
<ul>
<li>Python binding for curl-impersonate via cffi</li>
<li>Impersonate browser TLS/JA3/HTTP2 fingerprints</li>
<li>Requests-like API</li>
<li>HTTP/2 support</li>
<li>Async support (asyncio and trio)</li>
<li>Bypasses TLS fingerprinting-based bot detection</li>
<li>WebSocket support</li>
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
<li>⚠️ Largely unmaintained</li>
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

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.
