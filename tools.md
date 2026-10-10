# Tools Available to Jules

Below is a list of all tools available to Jules, along with the arguments they take (if any):

* `call_hello_world_agent`
  * `message` (string, required): The message to send to the Hello World agent.
* `create_file_with_block` *(deprecated)*
  * `filepath` (string, required): The path of the file to create.
  * `content` (string, required): The content to write to the new file.
* `delete_file`
  * `filepath` (string, required): The path of the file to delete.
* `done`
  * `summary` (string, required): A summary of what was accomplished or the final result.
* `frontend_verification_complete`
  * `screenshot_path` (string, required): The path to the screenshot of the frontend changes.
  * `additional_media_paths` (array of strings, optional): Optional list of paths to additional media files.
* `frontend_verification_instructions`
  * None
* `google_search`
  * `query` (string, required): The query to search for.
* `grep` *(deprecated)*
  * `pattern` (string, required): The pattern to search for.
* `initiate_memory_recording`
  * None
* `knowledgebase_lookup`
  * `query` (string, required): The query to search the knowledgebase for.
* `list_files`
  * `path` (string, optional): The directory path to list files from.
* `message_user`
  * `message` (string, required): The message to send to the user.
  * `continue_working` (boolean, required): Whether to continue working after sending the message.
* `overwrite_file_with_block` *(deprecated)*
  * `filepath` (string, required): The path of the file to overwrite.
  * `content` (string, required): The new content for the file.
* `plan_step_complete`
  * `message` (string, required): A succinct, descriptive message explaining what actions were taken.
* `pre_commit_instructions`
  * None
* `read_file`
  * `filepath` (string, required): The path of the file to read, relative to the repo root.
* `read_image_file`
  * `filepath` (string, required): The path of the image file to read.
* `read_media_file`
  * `filepath` (string, required): The path of the media file to read.
* `read_pr_comments`
  * None
* `record_user_approval_for_plan`
  * None
* `rename_file`
  * `filepath` (string, required): The original path of the file or directory.
  * `new_filepath` (string, required): The new path for the file or directory.
* `replace_with_git_merge_diff`
  * `filepath` (string, required): The path of the file to modify.
  * `merge_diff` (string, required): The diff to apply to the file.
* `reply_to_pr_comments`
  * `replies` (string, required): The replies to the comments in JSON string format.
* `request_code_review`
  * None
* `request_plan_review`
  * `plan` (string, required): The plan to be reviewed.
* `request_user_input`
  * `message` (string, required): The question or prompt for the user.
* `reset_all`
  * None
* `restore_file`
  * `filepath` (string, required): The path of the file to restore.
* `run_in_bash_session`
  * `command` (string, required): The bash command to run.
* `set_plan`
  * `plan` (string, required): The plan to solve the issue, in Markdown format.
* `start_live_preview_instructions`
  * None
* `submit`
  * `branch_name` (string, required): The name of the branch to commit to.
  * `commit_message` (string, required): The commit message.
  * `title` (string, required): The title of the submission.
  * `description` (string, required): The description of the submission.
* `view_image`
  * `url` (string, required): The URL of the image to view.
* `view_text_website`
  * `url` (string, required): The URL of the website to fetch.
* `write_file`
  * `filepath` (string, required): The path of the file to create or overwrite.
  * `content` (string, required): The content to write to the file.
