{
  "info": {
    "name": "Open Science Framework Actions",
    "_postman_id": "2181d28e-a550-4368-bbb0-4fb50414dada",
    "description": "A log can have one of many actions. The complete list of loggable actions (in the format {identifier}: {description}) is as follows:\n* `project_created`: A Node is created\n* `project_registered`: A Node is registered\n* `project_deleted`: A Node is deleted\n* `created_from`: A Node is created using an existing Node as a template\n* `pointer_created`: A Pointer is created\n* `pointer_forked`: A Pointer is forked\n* `pointer_removed`: A Pointer is removed\n* `node_removed`: A component is deleted\n* `node_forked`: A Node is forked\n---\n* `made_public`: A Node is made public\n* `made_private`: A Node is made private\n* `tag_added`: A tag is added to a Node\n* `tag_removed`: A tag is removed from a Node\n* `edit_title`: A Node's title is changed\n* `edit_description`: A Node's description is changed\n* `updated_fields`: One or more of a Node's fields are changed\n* `external_ids_added`: An external identifier is added to a Node (e.g. DOI, ARK)\n* `view_only_link_added`: A view-only link was added to a Node\n* `view_only_link_removed`:  A view-only link was removed from a Node\n---\n* `contributor_added`: A Contributor is added to a Node\n* `contributor_removed`: A Contributor is removed from a Node\n* `contributors_reordered`: A Contributor's position in a Node's bibliography is changed\n* `permissions_updated`: A Contributor`s permissions on a Node are changed\n* `made_contributor_visible`: A Contributor is made bibliographically visible on a Node\n* `made_contributor_invisible`: A Contributor is made bibliographically invisible on a Node\n---\n* `wiki_updated`: A Node's wiki is updated\n* `wiki_deleted`: A Node's wiki is deleted\n* `wiki_renamed`: A Node's wiki is renamed\n* `made_wiki_public`: A Node's wiki is made public\n* `made_wiki_private`: A Node's wiki is made private\n---\n* `addon_added`: An add-on is linked to a Node\n* `addon_removed`: An add-on is unlinked from a Node\n* `addon_file_moved`: A File in a Node's linked add-on is moved\n* `addon_file_copied`: A File in a Node's linked add-on is copied\n* `addon_file_renamed`: A File in a Node's linked add-on is renamed\n* `node_authorized`: An addon is authorized for a project\n* `node_deauthorized`: An addon is deauthorized for a project\n* `folder_created`: A Folder is created in a Node's linked add-on\n* `file_added`: A File is added to a Node's linked add-on\n* `file_updated`: A File is updated on a Node's linked add-on\n* `file_removed`: A File is removed from a Node's linked add-on\n* `file_restored`: A File is restored in a Node's linked add-on\n---\n* `comment_added`: A Comment is added to some item\n* `comment_removed`: A Comment is removed from some item\n* `comment_updated`: A Comment is updated on some item\n---\n* `embargo_initiated`: An embargoed Registration is proposed on a Node\n* `embargo_approved`: A proposed Embargo of a Node is approved\n* `embargo_cancelled`: A proposed Embargo of a Node is cancelled\n* `embargo_completed`: A proposed Embargo of a Node is completed\n* `retraction_initiated`: A Withdrawal of a Registration is proposed\n* `retraction_approved`: A Withdrawal of a Registration is approved\n* `retraction_cancelled`: A Withdrawal of a Registration is cancelled\n* `registration_initiated`: A Registration of a Node is proposed\n* `registration_approved`: A proposed Registration is approved\n* `registration_cancelled`: A proposed Registration is cancelled",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Actions",
      "item": [
        {
          "id": "af724601-4151-45b9-8d6a-4c3b8e3cf8c0",
          "name": "logs_actions",
          "request": {
            "url": "http://test-api.osf.io/v2/actions/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "A log can have one of many actions. The complete list of loggable actions (in the format {identifier}: {description}) is as follows:\n* `project_created`: A Node is created\n* `project_registered`: A Node is registered\n* `project_deleted`: A Node is deleted\n* `created_from`: A Node is created using an existing Node as a template\n* `pointer_created`: A Pointer is created\n* `pointer_forked`: A Pointer is forked\n* `pointer_removed`: A Pointer is removed\n* `node_removed`: A component is deleted\n* `node_forked`: A Node is forked\n---\n* `made_public`: A Node is made public\n* `made_private`: A Node is made private\n* `tag_added`: A tag is added to a Node\n* `tag_removed`: A tag is removed from a Node\n* `edit_title`: A Node's title is changed\n* `edit_description`: A Node's description is changed\n* `updated_fields`: One or more of a Node's fields are changed\n* `external_ids_added`: An external identifier is added to a Node (e.g. DOI, ARK)\n* `view_only_link_added`: A view-only link was added to a Node\n* `view_only_link_removed`:  A view-only link was removed from a Node\n---\n* `contributor_added`: A Contributor is added to a Node\n* `contributor_removed`: A Contributor is removed from a Node\n* `contributors_reordered`: A Contributor's position in a Node's bibliography is changed\n* `permissions_updated`: A Contributor`s permissions on a Node are changed\n* `made_contributor_visible`: A Contributor is made bibliographically visible on a Node\n* `made_contributor_invisible`: A Contributor is made bibliographically invisible on a Node\n---\n* `wiki_updated`: A Node's wiki is updated\n* `wiki_deleted`: A Node's wiki is deleted\n* `wiki_renamed`: A Node's wiki is renamed\n* `made_wiki_public`: A Node's wiki is made public\n* `made_wiki_private`: A Node's wiki is made private\n---\n* `addon_added`: An add-on is linked to a Node\n* `addon_removed`: An add-on is unlinked from a Node\n* `addon_file_moved`: A File in a Node's linked add-on is moved\n* `addon_file_copied`: A File in a Node's linked add-on is copied\n* `addon_file_renamed`: A File in a Node's linked add-on is renamed\n* `node_authorized`: An addon is authorized for a project\n* `node_deauthorized`: An addon is deauthorized for a project\n* `folder_created`: A Folder is created in a Node's linked add-on\n* `file_added`: A File is added to a Node's linked add-on\n* `file_updated`: A File is updated on a Node's linked add-on\n* `file_removed`: A File is removed from a Node's linked add-on\n* `file_restored`: A File is restored in a Node's linked add-on\n---\n* `comment_added`: A Comment is added to some item\n* `comment_removed`: A Comment is removed from some item\n* `comment_updated`: A Comment is updated on some item\n---\n* `embargo_initiated`: An embargoed Registration is proposed on a Node\n* `embargo_approved`: A proposed Embargo of a Node is approved\n* `embargo_cancelled`: A proposed Embargo of a Node is cancelled\n* `embargo_completed`: A proposed Embargo of a Node is completed\n* `retraction_initiated`: A Withdrawal of a Registration is proposed\n* `retraction_approved`: A Withdrawal of a Registration is approved\n* `retraction_cancelled`: A Withdrawal of a Registration is cancelled\n* `registration_initiated`: A Registration of a Node is proposed\n* `registration_approved`: A proposed Registration is approved\n* `registration_cancelled`: A proposed Registration is cancelled"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b75a172-7450-4aff-a052-c5cf14162552"
            }
          ]
        }
      ]
    }
  ]
}