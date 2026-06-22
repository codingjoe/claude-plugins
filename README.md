<img width="1280" height="640" alt="CodingJoe's Claude Code Marketplace" src="https://github.com/user-attachments/assets/93718504-bc00-42cf-9f22-7d554d62e3af" />

# CodingJoe's Claude Code Marketplace

A [Claude Code plugin marketplace](https://code.claude.com/docs/en/plugin-marketplaces)
collecting [codingjoe](https://github.com/codingjoe)'s skills and MCP servers.

## Plugins

| Plugin                                                      | Type        | Source                    | Description                                                                                        |
| ----------------------------------------------------------- | ----------- | ------------------------- | -------------------------------------------------------------------------------------------------- |
| [esupgrade](https://github.com/codingjoe/esupgrade)         | Skill       | `codingjoe/esupgrade`     | Auto-upgrade JavaScript and TypeScript syntax to new ECMAScript features based on browser support. |
| [VoIP](https://codingjoe.dev/VoIP/)                         | Skill + MCP | `codingjoe/VoIP`          | Async VoIP library for the AI age. Bundles an MCP server to make phone calls on your behalf.       |
| [naming-things](https://github.com/codingjoe/naming-things) | Skill       | `codingjoe/naming-things` | Naming conventions guidelines — solving computer science's second-hardest problem.                 |
| [reLint](https://github.com/codingjoe/relint)               | Skill       | `codingjoe/relint`        | Regular Expression Linter — write your own linting rules using regular expressions.                |
| [SuperJoe](https://github.com/codingjoe/superjoe)           | Skill + Agents| `codingjoe/superjoe`      | SuperJoe — CodingJoe's digital clone following his coding guidelines and best practices.           |

## Install

Add this marketplace and install any of its plugins:

```console
/plugin marketplace add codingjoe/claude-plugins
/plugin install esupgrade@codingjoe
/plugin install voip@codingjoe
/plugin install naming-things@codingjoe
/plugin install relint@codingjoe
/plugin install superjoe@codingjoe
```

## License

This marketplace catalog is provided as-is. Each plugin retains the license of
its source repository.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
