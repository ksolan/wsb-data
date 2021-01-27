## Reddit r/wallstreetbets hot posts dataset

The top 100 "hot" posts from r/wallstreetbets posts scraped every hour on the hour.

### Structure

Posts are stored in directories in the structure `<year>/<month>/<day>/<UTC timestamp>/`, indicating what date and time the scrape was run.

### File format

Posts are in .json format with a near-complete subset of fields returned from the Reddit API. The top three comments are saved, along with the top three replies, recursively, up to three levels deep.

### Usage

Usage is subject to the Reddit Terms of Service.

THE DATA ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE DATA OR THE USE OR OTHER DEALINGS IN THE DATA.
