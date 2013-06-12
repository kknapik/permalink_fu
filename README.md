== PermalinkFu

=== ActiveRecord plugin for creating permalinks

It's based on (https://github.com/technoweenie/permalink_fu)[https://github.com/technoweenie/permalink_fu]

    class Article < ActiveRecord::Base
      has_permalink :title
    end

Allowed options:

	* `:if`
	* `:unless`
	* `:unique`
	* `:scope`
	* `:update`

