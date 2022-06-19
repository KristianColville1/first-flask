# Simple Flask application

This repo is for learning how the python framework Flask interacts with web development.

## Important notes

On submitting projects of any kind change the debug value,

Reason: Security issue.

<!-- # debug must be set to false when submitting projects,
# its for production environments
if __name__ == "__main__":
    app.run(
        host=os.environ.get("IP", "0.0.0.0"),
        port=int(os.environ.get("PORT", "5000")),
        debug=True <HERE>
    ) -->