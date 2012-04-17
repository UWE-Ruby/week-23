!SLIDE

# Goals

!SLIDE bullets

## Understand the Code

* Important conceptual concepts
* Application flow
* Source code layout
* Unfinished areas
* Strengths
* Areas needing improvement
* Weaknesses

!SLIDE

## Original Source

    @@@ Ruby
    def loadJsonConfig(f)
      fd = File.open f
      h = JSON.parse(fd)
      return h
    end

!SLIDE

## Commented Source

    @@@ Ruby    
    # * Use a more descriptive variable names
    # * Use underscores in method name
    def loadJsonConfig(f)
      # Check for file existing
      fd = File.open f
      # Be more consistent with the () and when not using them
      # Check what is returned and default to a Hash if nil
      h = JSON.parse(fd)
      # Suggestion: Remove this return as it is understood
      return h
    end
    
!SLIDE

## Further Exercise

    @@@ Ruby
    
    # @param [String] filename the name of the JSON file 
    #                 to be opened.
    #
    # @return [Hash] the JSON data in Hash format, an empty
    #                Hash is returned when the file does not 
    #                exist or does not parse correctly as JSON.
    def load_json_config(filename)
      filedata = "{}"
      filedata = File.open(filename) if File.exist?(filename)
      begin
        JSON.parse(filedata)
      rescue
        {}
      end
    end
