This is the standard location for tests in suitcase.

However, for this specific suitcase the tests are located outside the
package, in the ``tests/`` directory at the top level of the repository.
This is to work around a bad interaction between
[pytest's test discovery mechanism](https://docs.pytest.org/en/latest/pythonpath.html),
namespace packages, and the fact that 'msgpack' is also the name of a Python
module. This issue does not interfere with the *usage* of
``suitcase.msgpack``, only with the operation of pytest.
